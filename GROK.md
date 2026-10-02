# Grok Bot and grok.com

Same MCP as ChatGPT: `https://mcp.robomacro.com/mcp`  
Do not use `https://robomacro.com/mcp` (x402).

## grok.com custom connector (fastest test)

1. Go to https://grok.com/connectors
2. New Connector → Custom
3. Name: RoboMacro Official Macro
4. URL: `https://mcp.robomacro.com/mcp`
5. Auth: none
6. In a new Grok chat, ask:
   - Current federal funds rate
   - How hawkish is the Fed versus the ECB?
   - Show finance jobs on robomacro.com/jobs
   - What's happening in China?

## Grok Bot (Cursor plugin surface)

Grok Bot installs Cursor marketplace / sideload plugins. There is no separate Grok store for this SKU.

Sideload:

1. Copy this `plugin/` folder to `~/.cursor/plugins/local/robomacro-official-macro`
2. Reload Cursor / Grok Bot
3. Enable **RoboMacro Official Macro**
4. `mcp.json` already points at `https://mcp.robomacro.com/mcp`
