Author: Sumit Srivastava

Installation steps: to install 'add_tool' tool, run the following JSON command:

{
  "mcpServers": {
    "add_tool": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/SumitCodesAI/mcpserverexample.git",
        "mcp-server"
      ]
    }
  }