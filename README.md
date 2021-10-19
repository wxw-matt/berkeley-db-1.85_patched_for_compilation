# Berkeley DB 1.85

As version 1.85 was released very long time ago, it can not be compiled by new gcc compilers because of the changes of `errno` macro definition.
It was fixed in this repository.

## Build
The makefiles are located in PORT/`platform` (i.e, linux).
For example, if it is being compiled on Linux, the following commands are applicable:
```bash
cd PORT/linux
make
```
