# Evaluation

**Hand-off decision accuracy** measures how often the bot's decision matches the expected decision.

`Accuracy (%) = (Correct hand-off decisions / Total hand-off test cases) × 100`

**Hand-off rate** measures the proportion of tested queries actually referred to a human.

`Hand-off rate (%) = (Queries actually handed off / Total queries tested) × 100`

A high hand-off rate is not automatically good: the bot may escalate routine questions unnecessarily. Review missed escalations and unnecessary escalations. Calculate using actual completed test results, not example values.
