# A Kernel Seedling
Intro: This lab entailed setting up a virtual machine in order to add a module to the Linux Kernel

## Building
```shell
TODO: cmd for build 
---> 'make'
```

## Running
```shell
TODO: cmd for running binary
---> 'cat /proc/count'
```
TODO: results?
---> '177'

## Cleaning Up
```shell
TODO: cmd for cleaning the built binary
---> 'make clean'
```

## Testing
```python
python -m unittest
```
TODO: results?
---> 'OK' (all tests passed)

Report which kernel release version you tested your module on
(hint: use `uname`, check for options with `man uname`).
It should match release numbers as seen on https://www.kernel.org/.

```shell
uname -r -s -v
```
TODO: kernel ver?
---> '5.14.8-arch1-1'