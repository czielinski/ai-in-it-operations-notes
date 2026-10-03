# Where AI may help

These are candidate tasks for a bounded evaluation. They are not claims of measured production benefits; whether they help depends on the data, task, users and effort needed to verify the output.

## Candidate tasks and the questions to test

| Task | Potential assistance | What to evaluate |
|---|---|---|
| Knowledge access | Find relevant runbooks and explain documented steps. | Correct and current sources, access boundaries, unsupported answers and appropriate abstention. |
| Drafting | Prepare change descriptions, incident updates or documentation drafts. | Factual accuracy, missing context and the time needed to review and correct the draft. |
| Triage | Suggest categories, routing or duplicate tickets. | Errors by category, consequences of misrouting and whether the suggestion improves on existing rules. |
| Summarisation | Assemble an incident timeline or condense operational notes. | Omitted evidence, invented causal claims and preservation of uncertainty. |

## Select a task with a usable baseline

Choose a task whose result a qualified user can assess. Record how the work is currently done and compare the proposed assistance with that process, including a simpler search or rules-based approach where relevant.

Use permitted examples covering routine work, difficult cases and missing or conflicting information. Define the acceptance criteria before testing, including the errors that would make the approach unsuitable. Count verification and correction effort alongside generation time.

## Keep assistance within its tested boundary

A useful draft or retrieved answer does not establish that the system can execute a production change safely. Changes to the task, data, model or permissions can require a new evaluation.

Record the baseline, results and continue/change/stop decision in the [AI pilot evaluation template](templates/ai-evaluation.md).
