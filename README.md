# Figma MCP Python

### For Cursor:
1. add  mcp  in cursor 

```
pipx run figma-mcp --figma-api-key=figma-apikey
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

