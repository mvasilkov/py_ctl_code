py_ctl_code
===

**CTL_CODE** from `ntddk.h`, written in Python.

The return value is compatible with the analogous C code.

**Usage:**

```Python
from ctl_code import *

a = CTL_CODE(FILE_DEVICE_UNKNOWN, 0x0701, METHOD_BUFFERED, FILE_SPECIAL_ACCESS)
hex(a)  # 0x221c04
```

[Docs][1]

[1]: https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/defining-i-o-control-codes
