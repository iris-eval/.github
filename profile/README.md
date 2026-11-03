# Iris

**Stop shipping agents on vibes.**

Iris is an open-source MCP server that evaluates AI agent output for quality, safety and cost, on your own machine. Send Iris a run and ask for a verdict: deterministic built-in rules check for PII, prompt injection, hallucination markers, cost and the agent's own tool calls; an optional model judge, on your own key and under a hard per-evaluation cost cap, answers the semantic questions. The verdict is pass, fail, or not checked when a required check could not run.

The precision and recall of every built-in rule are measured on a labelled corpus in the repository and published with confidence intervals on [the proof page](https://iris-eval.com/proof).

```bash
npx @iris-eval/mcp-server --demo
```

One command seeds a demo database and opens the dashboard on what failed, each failure naming its rule and its evidence. To score your own agent, start with the [README](https://github.com/iris-eval/mcp-server#readme).

| | |
|---|---|
| Code | [iris-eval/mcp-server](https://github.com/iris-eval/mcp-server), MIT licensed |
| Try it without installing | [The playground](https://iris-eval.com/playground) |
| What it can judge today | [The capability map](https://iris-eval.com/capabilities) |
| Ask a question | [Discussions](https://github.com/iris-eval/mcp-server/discussions) |
| Report a vulnerability | Privately, through [the security policy](https://github.com/iris-eval/mcp-server/security/policy) |
