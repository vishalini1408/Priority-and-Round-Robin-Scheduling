# Experiment 9: Priority and Round Robin Scheduling

**Course:** Operating Systems (21CSC202J)

This experiment contains the two C programs listed in the lab manual for Experiment 9.

## Files

- `priority_scheduling.c` — Airport runway landing order using priority scheduling.
- `round_robin_scheduling.c` — Airport taxiway order using Round Robin scheduling (time quantum = 2).
- `experiment9_priority_output.png` — Output screenshot from the lab manual.
- `experiment9_round_robin_output.png` — Output screenshot from the lab manual.

## 1. Priority Scheduling

Lower priority numbers indicate more urgent flights. The program sorts the flights by priority and assigns consecutive landing time slots.

Compile and run on Linux/Ubuntu:

```bash
gcc priority_scheduling.c -o priority_scheduling
./priority_scheduling
```

## 2. Round Robin Scheduling

Each flight gets up to 2 time units per turn. A flight that still has taxi time remaining gets another turn in the next cycle.

Compile and run on Linux/Ubuntu:

```bash
gcc round_robin_scheduling.c -o round_robin_scheduling
./round_robin_scheduling
```

**Note:** The PNG files preserve the output screenshots shown in the supplied manual. Terminal prompts may differ depending on the computer.
