# 🤖 AI Baseplate

**The open-source foundation for building AI applications.**
Stop copy-pasting boilerplate. Start with a solid base.

---

## What is this?

AI Baseplate is a community-driven starter kit — like `create-react-app` but for AI apps.
Pick a template, scaffold your project, and start building immediately.

## Quickstart

```bash
# Install
pip install ai-baseplate

# Scaffold a new project
ai-baseplate init my-ai-app --template chatbot

# Or add a template to an existing project
ai-baseplate add rag-app

# List all templates
ai-baseplate list
```

## Templates

| Template | Description |
|---|---|
| `chatbot` | Conversational AI with multi-turn memory |
| `rag-app` | Ask questions over your own documents |
| `multi-agent` | Multiple agents collaborating in a pipeline |

## Project Structure

```
ai-baseplate/
├── core/
│   ├── llm/          # Model connectors (Gemini, more coming)
│   ├── agents/       # Base agent loop
│   ├── memory/       # Vector DB integrations
│   └── tools/        # Web search, code exec, etc.
├── templates/
│   ├── chatbot/
│   ├── rag-app/
│   └── multi-agent/
├── cli/              # `ai-baseplate` CLI tool
└── docs/
```

## Supported Providers

| Provider | Status |
|---|---|
| Google Gemini | ✅ Supported |
| OpenAI / GPT | 🔜 Coming soon |
| Anthropic Claude | 🔜 Coming soon |
| Ollama (local) | 🔜 Coming soon |

## Contributing

Community templates are welcome! See [CONTRIBUTING.md](./CONTRIBUTING.md).

```
templates/
└── your-template/
    ├── main.py
    └── README.md     # explain what it does
```

## License

MIT — use it however you want.
