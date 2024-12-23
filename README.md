# avr-extends

Extensions to the avr MCU library provided by avr-gcc. The avr-gcc c-lib is very
limited and thus wrappers are needed for more complex functionality UART etc.

## Architecture

This library uses cmake and just requires the inclusion of:

```python
target_link_libraries([exe-name] PRIVATE avr-extends)
```

and

```python
add_subdirectory(libs/avr-extends)
```

See [embedded-terminal](https://github.com/jaxsonpd/embedded-terminal) or [flight-sim-software](https://github.com/jaxsonpd/flight-sim-software) for an example of this in action.

## Installation and git submodules

This library is designed to work as a git submodule as part of a larger project.

