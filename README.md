# testmyagent-demo-agent

A demo coding-agent definition for [Itera agent credentials](https://itera-agent-credentials.devfellowship.com).
Itera reads `AGENTS.md`, `CLAUDE.md` and `skills/**` from this repo at a pinned commit through the read-only
GitHub App, runs the agent against a benchmark in a sandbox, and issues an on-chain proof of the result.
