# cli-spinner

Spinners and progress bars that degrade gracefully when not a TTY.

## Why

Mostly written for my own projects, but it may be useful to someone else.

## Install

```bash
pip install cli-spinner
```

## Usage

```python
from cli_spinner import cliSpinner

result = cliSpinner("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
