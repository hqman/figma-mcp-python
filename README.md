# Figma MCP Python

### For Cursor:
1. OR Add a `.cursor/mcp.json` file in your project:

```json
{
	"mcpServers": {
		"figma-python": {
			"command": "uv",
			"args": [
				"--directory",
				"/yourpath/figma-mcp-python",
				"run",
				"figma-mcp-python.py"
			],
			"env": {
				"FIGMA_API_TOKEN": "figma-key"
			}
		}
	}
}
```



## Install uv and set up the environment
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
uv venv
source .venv/bin/activate
uv sync
```

## Test locally
```bash
python -m figma_mcp.main
```

