# Erico Virgy

I build AI automations and agents that act on real systems and stay under control: least-privilege access, human approval for risky actions, verification before a task is reported as done, and an audit trail.

Background: two and a half years as the sole owner of identity and access (Google Workspace, then Microsoft 365 and Entra ID) at a national confederation with no IT team. Before that, two years managing a EUR 1 million funded programme and a national public funding process, and six years coordinating external relations as a volunteer. Based in Portugal.

## Start here

| Project | What it shows |
|---|---|
| [ai-automation-harness](https://github.com/ericovirgy/ai-automation-harness) | Controls for AI tool calls: deny-by-default policy, single-use human approvals bound to exact arguments, verification states and a hash-chained audit log. Reference implementation with simulated tools. |
| [m365-access-audit](https://github.com/ericovirgy/m365-access-audit) | Read-only Microsoft Graph access review with five least-privilege permissions. Automates the review I used to run by hand. |
| [local-llm-security-evaluator](https://github.com/ericovirgy/local-llm-security-evaluator) | 38 reproducible adversarial scenarios for local LLMs, scored with deterministic checks instead of an LLM judge. |
| [agentic-web-check](https://github.com/ericovirgy/agentic-web-check) | CLI that tests whether AI agents can use a website: 43 checks, task verdicts and a safety review. Published on npm. |

Also: my final assignment for the [Hugging Face Agents Course](https://huggingface.co/spaces/ELRomeu94/GAIA-Agent-Final-Assignment), a smolagents agent with nine tools.

## How these projects are built

I define the scope, the controls and the acceptance criteria, and I build with AI coding assistants (Claude Code). I check the results with tests and CI, and each repository documents its limitations. These are independent projects, not production systems.

[LinkedIn](https://www.linkedin.com/in/erico-virgy)
