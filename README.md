# Python Special Methods Assignment


## What Are Special Methods?

Methods with double underscores like `__init__` that hook into Python's built-in features.

## Methods Covered

| # | Method | What It Does | Trigger |
|---|--------|-------------|---------|
| 1 | `__init__` | Create object | `Class()` |
| 2 | `__str__` | Pretty print | `print(obj)` |
| 3 | `__repr__` | Debug view | `repr(obj)` |
| 4 | `__len__` | Count items | `len(obj)` |
| 5 | `__eq__` | Check equal | `==` |
| 6 | `__lt__` | Less than | `<` |
| 7 | `__add__` | Add objects | `+` |
| 8 | `__getitem__` | Get by index | `obj[i]` |
| 9 | `__setitem__` | Set by index | `obj[i] = x` |
| 10 | `__contains__` | Check inside | `in` |
| 11 | `__call__` | Call like function | `obj()` |
| 12 | `__iter__` / `__next__` | Loop | `for x in obj` |
| 13 | `__bool__` | True or False | `if obj:` |
| 14 | `__del__` | Cleanup | `del obj` |
| 15 | `__enter__` / `__exit__` | Safe block | `with obj:` |
| 16 | `__hash__` | Dict/set key | `hash(obj)` |

## How to Run

Open `python_special_methods.ipynb` in Jupyter, VS Code, or Google Colab and run each cell.

Author
DARCELLE EYRAM KPODO
