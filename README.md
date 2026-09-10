T2K-NOvA JSON Schemas for NuDock.

## Layout

```
schemas/<command>.schema.json
```

### Commands

| Schema | Purpose |
| --- | --- |
| `ping` | Liveness check |
| `get_parameter_names` | List the oscillation and systematic parameter names |
| `set_parameters` | Set oscillation and systematic parameter values |
| `set_asimov_point` | Set the current parameters as the Asimov point |
| `log_likelihood` | Get $-2\log L$ at the current parameter point |


### To be confirmed

| Schema | Purpose |
| --- | --- |
| `get_data_spectrum` | Binned data spectra |
| `get_mc_spectrum` | Binned MC spectra |

### Optional

| Schema | Purpose |
| --- | --- |
| `get_parameters` | Get current systematic parameter values (useful for debugging) |
