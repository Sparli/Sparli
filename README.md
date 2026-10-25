### Sparli Aman: AI engineer, agent integrations

I build AI agents that act on real systems, like phone lines, CRMs and internal tools, and the
guardrails that make them safe to run: validated tool calls, human approval before writes, audit
trails, and cost per run.

**Open to:** AI / agent engineering roles, remote, or on-site in Germany.
**More:** [sparli.dev](https://sparli.dev): case studies from client work.

---

#### Featured

**[leadflow-agent](https://github.com/Sparli/leadflow-agent)**: a Claude tool-using agent that turns a raw
sales enquiry into de-duplicated, linked HubSpot records.
- The model proposes; a human approves; only then does code write to the CRM.
- Every tool call is schema-validated, every write is logged in an audit ledger and reversible in one command.
- Hand-written, step-capped agent loop with cost per run (under $0.002 per lead on Haiku in live runs).

**[sparli-dev](https://github.com/Sparli/sparli-dev)**: my site. Static, zero client JS, deployed through CI;
a performance budget and a content schema fail the build.

---

#### How I work
- **Prompts are requests, code is enforcement.** Anything an agent does goes through validation first.
- **Humans approve consequential actions.** Draft, then approve, never silent auto-execution.
- **Measure it.** Cost, latency and accuracy are outputs, not guesses. Limitations are written down.

Python · Anthropic API · tool use · HubSpot · FastAPI · telephony / voice · pydantic · SQLite · CI/CD

<sub>I use AI-assisted tooling openly and can walk through every design decision in these repos.</sub>
