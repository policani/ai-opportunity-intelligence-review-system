# Value And Proof Review

Evaluate whether the use case has credible value.

Value categories:

- Time saved
- Quality improved
- Cycle time reduced
- Risk reduced
- Revenue enabled
- Cost avoided
- Decision speed improved
- Customer or employee experience improved
- Compliance or control strengthened

Proof questions:

- What expected outcome is the AI idea meant to improve?
- What benefit type is being claimed: hard financial, cost avoidance, revenue protection, risk reduction, quality/rework, cycle time, customer/employee experience, compliance/control, mission value, or strategic option value?
- What metric, baseline, target, measurement period, source, measure owner, and review cadence would make the claim inspectable?
- What validation is needed, who must provide it, and what finance-sensitive flag should be carried?
- What confidence level and realization risk should be carried forward?
- What downstream route should receive the value claim if the opportunity proceeds?
- What would count as success?
- Can success be measured within a small test?
- What baseline exists?
- What evidence is missing?
- What is the cheapest credible proof?
- What would cause the team to stop?
- Is a POC cheaper than a decision workshop, process map, vendor trial, manual test, or no action?

## AI true-cost questions

Before a value claim is treated as investment-ready, ask:

- What model, token, vendor, license, or usage assumptions drive run cost?
- What connector, integration, retrieval, data-cleanup, or workflow-harness work is required?
- What prompt, evaluation, test-set, logging, monitoring, and rollback work is required?
- How much human review, exception handling, rework, training, support, and change management is needed?
- Who owns operations after the proof: support, access, model changes, prompt drift, data updates, and incident response?
- What is the cheapest credible proof: no action, process map, manual test, existing tool, vendor trial, prototype, build, buy, hire/upskill, wait, or stop?

Do not manufacture ROI. Flag unsupported benefit claims and cost uncertainty.
Do not treat a demo, model choice, usage volume, token spend, or launch as value
realization. If true cost or workflow shape is unclear, route to Process-First,
Decompose Further, Wait, or Stop rather than forcing a proof plan.

## Published Benchmark Ranges

Use these to calibrate whether a value claim is in a plausible range. They are not targets and do not transfer to your workflow without a baseline. Ranges depend on workflow type, volume, human review burden, exception rate, and deployment maturity.

| Value category | Illustrative published range | Source and context |
|---|---|---|
| Document or contract review cycle time | 45–90% reduction in review time | JPMorgan COiN: 12,000 credit agreements per year, formerly ~360,000 lawyer-hours. Sirion enterprise redlining data: 45–90% reduction in playbook cycle time. Pharma deployments: days-to-hours reduction in regulatory review. |
| Decision memo and report production | 30% faster; 2× RM productivity | McKinsey (2024): North American bank credit risk memos via multiagent system — previously 1–3 days per memo across 12+ data sources. Revenue per relationship manager rose 20%. |
| Knowledge retrieval during service or operations delivery | 30–65% reduction in handle time | McKinsey (2024): European telecom gen AI agent copilot — 65% reduction in knowledge-retrieval handle time; overall call volume fell ~30%; first-call resolution up 10–20 percentage points. |
| Knowledge worker task completion speed | 12–56% faster (context-dependent) | GitHub Copilot controlled study (Microsoft/Harvard, 2023): 55.8% faster task completion (2h41min → 1h11min). Field deployment across 1,974 developers: 12–22% more pull requests per week. Task-level speed gains are larger than full workflow throughput gains — match the proof metric to the actual workflow, not the task benchmark. |
| Meeting and documentation overhead | 1–4+ hours per person per week | Otter.ai survey (2024, n=600 professionals): 62% saved 4+ hours/week on meeting notes. Sales teams with AI-CRM auto-sync: 8–12 hours/rep/week. Varies significantly by meeting frequency and current process quality. |
| Financial planning and analysis operating cost | $6M–$10M OpEx reduction (specific deployment) | McKinsey (2024): Consumer goods company gen AI copilot for FP&A. Finance-validated against that company's cost structure — not a general benchmark. |
| Project timeline and delivery accuracy | 15–30% improvement in on-time delivery | Published PMO and forecasting studies (2024–2025): AI-driven scheduling and forecasting tools associated with up to 30% reduction in project delays and 25% reduction in budget overruns. Directional; depends on data quality, adoption depth, and process maturity. |

## Reference Examples

Specific, citable deployments in operations and decision-support contexts. Each includes what the workflow was, what the AI did, what was measured, and how proof was established.

**Credit risk memos — North American bank (McKinsey, August 2024)**
Relationship managers previously spent 1–3 days per memo gathering data from 12+ sources to write 20-page credit memos. A multiagent gen AI system now identifies sources, ingests current data, integrates qualitative and quantitative analysis, and cites each assumption. Measured result: credit decisions 30% faster; RM productivity more than doubled; revenue per RM up 20%. Proof path: staged deployment with human review; RM productivity and revenue tracked over time. Source: McKinsey, "From promising to productive: Real results from gen AI in services," August 2024.

**Contract review — JPMorgan COiN (launched 2017, publicly documented)**
Machine learning model parses 12,000 commercial credit agreements per year, extracting 150 data attributes per document. Formerly ~360,000 lawyer-hours annually. Error rate dropped approximately 80%. Proof path: parallel baseline testing against human review; multi-year operation. Note: mature deployment in a bounded, structured document type — not a proxy for unstructured or variable-format document review.

**Customer service knowledge retrieval — European telecom (McKinsey, August 2024)**
Gen AI copilot provided real-time knowledge retrieval for agents during live calls. Agent ratings collected weekly; qualitative feedback gathered in working groups. Result: 65% reduction in handle time for knowledge retrieval; total call volume fell ~30%; first-call resolution up 10–20 percentage points. Proof path: agent feedback loops, quantitative ratings, staged rollout with change management investment. Source: McKinsey, "From promising to productive: Real results from gen AI in services," August 2024.

**Developer task speed — GitHub Copilot (Microsoft/Harvard, 2023; Communications of the ACM)**
Controlled study (95 professional developers): task completion time fell from 2h41min to 1h11min (55.8% faster). Field study (1,974 Microsoft and Accenture developers): 12–22% more pull requests per week. Controlled task-level speed gains are materially larger than real-world workflow throughput gains — plan your proof to match the actual workflow metric, not the task-level benchmark. Source: GitHub, Microsoft Research, Communications of the ACM (2023).

Use these examples to test whether a claimed benefit is in a credible range, to design a proof that matches the actual workflow, and to ask what baseline, measurement owner, and evidence would be required before the claim is treated as investment-ready.
