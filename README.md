
# mcp-server-workshop


### Test 1
```zsh
echo '{"jsonrpc": "2.0", "id": 1, "method": "tools/call", "params": {"name": "add", "arguments": {"a": 5, "b": 3}}}' | node mcp.js | jq
```