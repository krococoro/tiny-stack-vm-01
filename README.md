# tiny-stack-vm-01 entry — tiny stack VM in one Node program

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/krococoro/tiny-stack-vm-01/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/krococoro/tiny-stack-vm-01/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A faithful port of the kit's reference VM (`vm.mjs`) in a single `main.ts`:
32-bit wrapping integers, `Math.imul` MUL, unsigned DIVU/MODU/LTU, all ten
traps with their own exit codes, 256-value stack, 64-deep call stack, 256
words of memory, a 1,000,000-step limit and a 65,536-byte output limit.
Node 22, built-ins only, fully deterministic — no network, clock or
randomness. Run: `node main.ts` with `MAKEFUN_INPUT_DIR` /
`MAKEFUN_OUTPUT_DIR` set; it answers all 40 instances in one run.

Practice set: score **1,000,000** (40/40 instances, passed) vs the house
baseline plain-vm 1.0.0 at 670,000. MIT licensed.
