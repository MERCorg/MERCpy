# Overview

A set of Python utilities used for artifacts.


## Usage

This module can be used by importing it as a module in your Python scripts:

```python
import os
import sys

# Get the script directory
SCRIPT_DIR = os.path.dirname(os.path.abspath(__file__))

# make parent directory importable so we can import merc as a module
sys.path.insert(0, "..." / "merc-py"))
from merc import RunProcess, MercLogger
```

## Testing

```bash
python -m unittest discover -s merc/tests
```