# An operating model for AI in operations

An AI-supported operational task needs a defined service boundary: what it may do, who relies on it, what data it can access and how the work continues when its output is wrong or unavailable.

## Ownership and data

Name the owner of the supported process and the parties responsible for the AI service, its data sources and its access controls. Agree permitted data, retention and service use through the organisation's relevant approval process.

For knowledge access, a user should only receive information they are entitled to see. Treat retrieved documents and tickets as input data; instructions embedded in them must not acquire authority to change the task or grant access.

## Evaluation and change

Use representative, permitted cases with expected outcomes or a clear assessment rubric. Include missing information, contradictory sources and cases that should be declined. External benchmarks can inform selection, while task-specific testing is needed to judge suitability for the intended workflow.

Version the relevant model configuration, prompts and source material. Re-evaluate after material changes and when observed errors suggest the existing test set no longer covers the work.

## Operation and human control

Specify who reviews the result, how to reach support and how to use the existing process without AI assistance. Monitor quality, verification effort, cost and failures that matter to the task. Set the review cadence according to usage and impact, alongside reviews triggered by changes or incidents.

If the system can act, define narrowly scoped permissions, approval points, audit records and recovery arrangements. Successful drafting or question answering is insufficient evidence for expanding those permissions. Reviewers also need the time and information to check the output meaningfully.

The [pilot evaluation template](templates/ai-evaluation.md) records the evidence and conditions for continuing, changing or stopping an evaluation.
