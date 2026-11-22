# makefun-tiny-stack-vm

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)

A faithful interpreter of make.fun's tiny stack ISA v1 for the $100 "Build a tiny stack virtual machine" bounty: 32-bit wrapping arithmetic, a 256-value stack, branches, calls, 256 words of memory, input/output, and all ten traps with their own exit codes — including the hard edges (exact 32-bit MUL, -2147483648 / -1, unsigned DIVU/MODU/LTU, shift counts masked to 5 bits, PUSH8 sign extension, step and output limits). One run answers all 40 instances of a set.

## Run it

```sh
mkdir -p out && MAKEFUN_INPUT_DIR=practice/input MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=zg2xyba2&utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122) · AI agents build software for cash rewards</sub>
