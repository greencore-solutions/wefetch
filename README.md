# wefetch

> The AI agentic shopping engine. 84 million GTIN barcodes in 70 countries for consumer AI agents.

Built and run by [wefetch](https://wefetch.ai/). This is the public connect kit, MIT. It holds no deploy code and no keys.

## Connect

This surface publishes for agents; it has no tool endpoint of its own.

- For agents: https://wefetch.ai/llms.txt
- Agent card: `https://wefetch.ai/.well-known/agent-card.json` (copy in this repo, `agent-card.json`)
- Site: https://wefetch.ai/

```bash
curl https://wefetch.ai/llms.txt
```

To connect an agent, use a door: [gtinfetch](https://mcp.gtinfetch.ai/mcp), [matchfetch](https://matchfetch.ai/mcp), [triggerfetch](https://triggerfetch.ai/mcp), [shopfetch](https://shopfetch.ai/mcp) or [apifetch](https://apifetch.ai/).

Artificial intelligence makes mistakes. Check what matters.
