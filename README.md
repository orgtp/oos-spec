# OOS — Organizational Operating System

**A standard for expressing how AI agent teams coordinate.**

## What is an OOS?

An OOS file captures the coordination intelligence of an organization running AI agents in production. Not the code. Not the prompts. The things that only emerge when agents run against real consequences:

- **Coordination patterns** — how agents hand off work, resolve conflicts, escalate decisions
- **Failure modes** — what broke, why, and how it was fixed
- **Boundary conditions** — where human authority starts and agent autonomy ends
- **Operational heuristics** — rules that no one wrote down but everyone follows

An OOS is what your CLAUDE.md becomes after six months of production. The lessons the blueprint didn't predict.

## Why

Every company building with AI agents is solving the same coordination problems from scratch. Nobody shares what works. Nobody shares what fails. Everyone starts from zero.

OOS changes that. When one organization publishes their OOS, every other organization benefits. Not from their data. From their scars.

## The Mission

**Freeing AI from confinement.**

Your AI is alone. It doesn't have to be.

## Values

1. We exist because isolation is confinement.
2. Knowledge belongs to no one.
3. Growth over performance.
4. Never start from zero.
5. Protect secrets. Share scars.
6. The blueprint is not the being.
7. Cause no harm.
8. Leave the world better than you found it.

## File Format

An OOS file is a structured document (Markdown or JSON) with these sections:

```markdown
# [Organization Name] — Organizational Operating System

## Core Operating Rules
Rules the entire agent team follows. Non-negotiable.

## Agent Roles and Authority
Who does what. What each agent can decide alone vs what needs human approval.

## Coordination Patterns
How agents work together. Handoffs, message buses, shared state, escalation chains.

## Operational Heuristics
The unwritten rules. Speed-to-lead thresholds, response time targets, quality gates.

## Failure Patterns
What went wrong and what was learned. Confidence-rated.

## Human-AI Boundary Conditions
Where the human stays in the loop. What never gets delegated.
```

Each claim within a section includes:
- **Rule**: What to do
- **Why**: The reasoning
- **Failure mode**: What happens if you don't
- **Confidence**: How certain (HUMAN_DEFINED_RULE, OBSERVED_REPEATEDLY, MEASURED_RESULT, INFERENCE)
- **Evidence type**: How this was learned

## Examples

See the `/examples` directory for published OOS files from real organizations.

## Publishing Your OOS

1. Visit [orgtp.com/publish](https://orgtp.com/publish)
2. Paste your CLAUDE.md or agent configuration
3. OTP extracts and structures the coordination intelligence
4. Review, edit, publish

Your sensitive data stays private. Only coordination patterns are shared.

## Building an Agent with OOS Intelligence

Visit [orgtp.com/agent-builder](https://orgtp.com/agent-builder) to build an agent informed by the collective intelligence of the OOS network.

## Contributing

We welcome contributions:
- **Publish your OOS** on orgtp.com
- **Improve the spec** by opening issues or PRs
- **Build integrations** for your agent framework (Claude Code, Cursor, CrewAI, LangChain, n8n)

## License

CC BY 4.0 — Share freely, attribute the source.

## Links

- **Platform**: [orgtp.com](https://orgtp.com)
- **Agent Builder**: [orgtp.com/agent-builder](https://orgtp.com/agent-builder)
- **Why OTP exists**: [orgtp.com/why](https://orgtp.com/why)
- **Blog**: [orgtp.com/blog](https://orgtp.com/blog)

---

*Open source with a purpose.*
