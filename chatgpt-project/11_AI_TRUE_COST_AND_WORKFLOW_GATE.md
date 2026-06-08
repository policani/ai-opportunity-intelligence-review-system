# AI True-Cost And Workflow-Shape Gate

Use this gate before recommending build, buy, prototype, or scale investment.
The question is not "can AI do something?" The question is whether the work is
described well enough, valuable enough, and cheap enough to justify the next
step.

## Gate 1 - Work Description

Require plain-English answers:

- Trigger or intake signal
- Inputs, source systems, documents, or events
- Output the workflow must produce
- Downstream user, decision, or system
- Exceptions and edge cases
- Human review point
- Escalation condition
- Error bounds and consequence of error
- Data permissions, privacy limits, and access constraints
- Support owner after launch

If these are missing, route to Process-First, Decompose Further, Wait, or Stop.

## Gate 2 - True Cost

Capture the cost shape without inventing false precision:

- Model, token, vendor, license, and usage assumptions
- Connector, integration, retrieval, data-cleanup, and workflow-harness work
- Prompt design, evaluation set, logging, monitoring, and rollback effort
- Human review, exception handling, rework, training, support, and change management
- Security, legal, privacy, procurement, architecture, and finance review needs
- Operating owner for access, model changes, prompt drift, data updates, incidents, and retirement

Mark each field as known, provisional, missing, or not applicable.

## Gate 3 - Cheapest Credible Proof

Compare AI against:

- No action
- Stop low-value work
- Process map
- Manual sample
- Existing-tool configuration
- Rules-based automation
- Vendor trial
- Decision workshop
- Prototype
- Build
- Buy
- Hire or upskill
- Wait

Recommend the smallest route that can answer the decision. Do not use a
prototype when a workshop, manual sample, or existing-tool configuration is
enough.

## Gate 4 - Value Claim Control

Tie the idea to the measurement contract. Do not count demos, usage volume,
token spend, model choice, launch, or user enthusiasm as value realization.
Flag unsupported benefits, finance-sensitive claims, cost uncertainty, and
missing baselines.

## Output

Return:

- Gate result: pass, conditional pass, process-first, decompose, wait, or stop
- Recommended route: prototype, build, buy, automate with existing tools, hire/upskill, wait, process-first, decompose further, or stop
- True-cost summary
- Unsupported claims
- Cheapest credible proof
- Human decision needed
