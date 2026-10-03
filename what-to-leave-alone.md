# Boundaries for an initial AI pilot

For an initial evaluation, choose a task where an error can be detected and contained before it causes operational harm. The following boundaries help define that scope; any later expansion needs evidence and a separate decision about the added risk.

## Production changes

Start with analysis or proposals that a qualified person can review. Production write access requires a defined action scope, authorised permissions, approval rules, auditability and recovery. General confidence in a model is not an adequate basis for granting it broad infrastructure access.

## Alert suppression

Evaluate suggested grouping or prioritisation while preserving the original alerts and existing response path. Measure missed important cases as well as reduced noise. Suppressing alerts changes the information available to responders and needs its own acceptance criteria.

## Unapproved data or access

Use data and services approved for the intended task. Define who may retrieve which material and what may be retained. Test those boundaries with permitted examples before introducing operational information.

## Results that cannot be checked

A reviewer needs relevant evidence and enough time to assess it. A fluent explanation or a linked source does not by itself establish correctness. Prefer tasks with observable outcomes and a clear response to uncertainty.

## Dependence without a fallback

Plan for unavailable services, incorrect output and changes in the supplier's terms or capabilities. Preserve the information and process needed to continue the work. Logging should support investigation while respecting data-handling and retention requirements.

Record the boundaries and stop conditions in the [pilot evaluation template](templates/ai-evaluation.md). If a failure cannot be contained within them, narrow the task or choose a different approach.
