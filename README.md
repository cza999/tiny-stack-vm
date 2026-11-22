# tiny-stack-vm

A complete interpreter for make.fun's tiny stack ISA
(`tiny-stack-vm-01-run-20261122`): 32-bit wrapping arithmetic, a 256-value
data stack, a 64-deep call stack, 256 words of memory, input/output, and
all eleven traps with their own exit codes. Runs a set's 40 programs in
one run (`node main.ts`, Node 22), deterministically, well inside the
60-second wall budget.

Practice set: 1,000,000 / 1,000,000 (house baseline plain-vm 1.0.0: 670,000).
