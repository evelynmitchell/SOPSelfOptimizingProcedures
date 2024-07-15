# SOPSelfOptimizingProcedures

## Society of Agents Hackathon 2024-07-13
## Self-improving Standard Operating Procedures
### Evelyn Mitchell (github/evelynmitchell)
### Nicholas Del Negro (github.com/OSOSerious)

Workflows are crucial for improving processes, but they need regular improvement as the world changes.

This project, inspired by the Swarms SOPs and [TextGrad](https://arxiv.org/abs/2406.07496) will take a simple instruction for a task, and ask an agent to complete it. Another agent, the Evaluator, will evaluate (Good/Bad) the output of the task. If the output of the task is Good the instructions will be unchanged. If the output of the task is Bad, a third agent, the Optimizer, will look at the original prompt and the output and suggest improvemnts to the original prompt.

This project won second place in the hackathon.