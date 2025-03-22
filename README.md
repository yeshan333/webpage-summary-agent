# Webpage Summary Agent with mcp-agent and qwen

[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

## Require

- Windows environment
- [uv](https://github.com/astral-sh/uv)

## Installation

```bash
uv venv
```

## Usage

Create file `mcp_agent.secrets.yaml`，set qwen api key in `mcp_agent.secrets.yaml`:

```yaml
# mcp_agent.secrets.yaml
# key from: https://bailian.console.aliyun.com/?apiKey=1#/api-key
openai:
  api_key: "sk-xxxxxx"
```

```python
uv run main.py --url "https://docs.cline.bot/improving-your-prompting-skills/prompting#advanced-prompting-techniques"
```

## Acknowledgements

- [mcp-agent](https://github.com/lastmile-ai/mcp-agent)
