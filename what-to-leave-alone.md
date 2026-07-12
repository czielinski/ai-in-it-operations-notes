# What to leave alone

Not forever. Just not first, and not without a track record.

**Autonomous change execution in production.** A system that acts on infrastructure without a human decision combines the two things you least want together: high blast radius and unclear accountability.

**Automatic alert suppression.** Letting a model decide which alarms are noise is an elegant way to sleep through the one that was not.

**Actions without logs.** Anything an AI system does must be attributable and reconstructable. No log, no action. This is not an AI rule; it is an operations rule that AI does not get to skip.

**Sensitive data without explicit clearance.** Health-related, personal, or otherwise protected data does not enter any AI system on the strength of enthusiasm. Clearance first, capability second.

**Systems whose failure modes you cannot explain.** If nobody can say how the capability fails and what happens then, it has no place in an operational chain.

**Vendor magic without an exit.** Any AI capability woven into operations needs the same exit path as any other sourcing decision: your data comes back, your process survives the vendor.

The pattern behind the list: operations runs on accountability, attribution, and reversibility. Tools that weaken those three do not become acceptable by being impressive.
