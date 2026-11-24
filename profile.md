# Prateek Kapoor

Hands-on cloud engineering leader building practical engineering agents, evaluation systems, and developer infrastructure.

- Website: https://pkapoor2.github.io/AboutMe/
- Current role: Senior Cloud Engineering Manager, HPE Aruba Networking
- GitHub: https://github.com/pkapoor2
- LinkedIn: https://www.linkedin.com/in/prateek-kapoor83/
- Email: prateek.kapoor83@gmail.com
- Updated: November 24, 2026

## Leadership and engineering scope

I lead 15 direct reports and stay close to the code: building agent infrastructure, evaluating behavior, and turning experiments into useful engineering workflows. My foundation is networking, distributed systems, and test automation. My professional agent work began in 2025.

- Approximately 270 engineers use the agent platform daily, measured through router OpenTelemetry instrumentation.
- Two live engineering agent systems support networking / web testing and monitoring workflows.

## Journey: from makemore to engineering agents

1. **Learn:** hands-on work with [Andrej Karpathy's makemore](https://github.com/karpathy/makemore) built an understanding of model behavior beyond the API surface.
2. **Build:** I built initial components spanning a Python harness, multi-agent orchestration, federated MCP tools, a gateway and skills, routing, retrieval, and evaluation.
3. **Evaluate:** bounded review loops, explicit acceptance decisions, and persisted outputs make improvements inspectable against workflow outcomes.
4. **Enable:** the team extended retrieval and routing and built the private inference stack. Together, we power live engineering agents for everyday work.

## Agent architecture and engineering practices

- **Execution:** Python harnesses and multi-agent orchestration connect local inference to engineering tools through federated MCP and a gateway, with vLLM integration.
- **Context:** GraphRAG with Neo4j / FalkorDB supports contextual retrieval. Routing and evaluation shape context and output acceptance.
- **Review:** a budget-bounded ratchet reviews an inner directed acyclic graph (DAG). A frontier-model judge guides context or parameter refinement, and accepted outputs are persisted.
- **Memory:** Dream rounds promote reusable skills and retire stale knowledge. Evaluation, tests, and telemetry guide subsequent iterations.
- **Control:** RBAC role permissions constrain actions, with selective human escalation through email, chat, or Slack.
- **Observability:** OpenTelemetry provides routing and usage signals. Latency and token budgets are explicit engineering tradeoffs.
- **Craft:** test-driven development, architecture decision records, and hands-on implementation build system quality and team capability.

## Technical toolkit

Python / Pytest; MCP; OpenTelemetry; REST / GraphQL; Playwright; Docker / Kubernetes; vLLM / local inference; GraphRAG; Neo4j / FalkorDB; distributed systems; networking / cloud systems; TDD; architecture decision records.

## Career

| Period | Role | Organization |
| --- | --- | --- |
| October 2024 – present | Senior Cloud Engineering Manager | HPE Aruba Networking |
| February 2022 – October 2024 | System Test Manager · Cloud Services & AI Initiatives | HPE Aruba Networking |
| February 2018 – February 2022 | System Test Engineer for Cloud Services | HPE Aruba Networking |
| January 2017 – December 2017 | Research Assistant | Binghamton University |
| October 2013 – August 2016 | Member of Technical Staff 4 (MTS4) | Aruba |
| November 2012 – October 2013 | Module Lead | Calsoft |
| May 2012 – October 2012 | Quality Assurance Engineer | Sandvine |
| January 2011 – May 2012 | Layer 3 Global support | Aricent |
| June 2007 – January 2011 | Senior Engineer Testing | Aricent |

## Personal engineering benchmark

In my personal engineering benchmark, Qwen3-235B local execution with a frontier judge reached the same outcome as a frontier-only run.

| Approach | Paid token spend | Elapsed time |
| --- | --- | --- |
| Local execution + frontier judge | $0.03 | 31 minutes |
| Frontier-only run | $5.71 | 6 minutes |

The local execution approach cut paid token spend while taking longer to complete. The comparison measures paid token spend and elapsed time for the same task.

[Read the personal benchmark on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7492463745756139520/).

## Education and academic research

- Post Graduate Program in AI / ML — Purdue, 2025
- MS, Computer Science — Binghamton University, 2017
- Master of Computer Applications — Thapar, 2007

Academic research: detecting and mitigating spoofing attacks against automotive radar.

[Academic publication on IEEE Xplore](https://ieeexplore.ieee.org/document/8506579).

## Opportunities

Open to hands-on Engineering Manager / Senior Engineering Manager roles, and individual-contributor opportunities in agent infrastructure, evaluation, and developer experience.