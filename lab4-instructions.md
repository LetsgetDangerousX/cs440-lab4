# Lab 4 Instructions (reference)

Copied from the Lab 4 assignment so the agent's Lab 4 run can be checked against it.
The submission logistics (Canvas, video) are omitted.

## Task

Lab: vacuum robot using reinforcement learning.

The vacuum robot will use the environment below. However, we don't have T and R
as we expected. We want to implement Q-learning (later, not today).

|       |    |   |    |
| ----- | -- | - | -- |
| start | 0  | 0 | 0  |
| 0     | X  | 0 | 0  |
| 0     | 0  | 0 | 0  |
| 0     | -1 | 0 | 10 |

Create one repository for context engineering strategies 1 and 4. The repository
must contain all files with appropriate content.

Deliverables: a link to the repositories configured with each context engineering
strategy, and a README documenting the project structure.

## Reference solutions

The team's own Lab 4 submissions are the comparison target for the mini agent's run:

| Strategy | Repository | Lab 5 skill that came from it |
| --- | --- | --- |
| 1, memory (keyword-triggered context hook) | `CS440-Lab4-Strat1` | `hook-check` |
| 4, isolation (bounded specialist agents) | `CS440-Lab4-Strat4` | `delegate` |

Lab 4 is configuration only: no environment code and no Q-learning.
