# mains09satrapy-kit

Count lines, words and characters, with totals.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m mains09satrapy_kit.cli --help
```

```python
from mains09satrapy_kit.core import Mains09satrapyTool

tool = Mains09satrapyTool()
print(tool)
```

## Layout

```
mains09satrapy_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 mains09satrapy
