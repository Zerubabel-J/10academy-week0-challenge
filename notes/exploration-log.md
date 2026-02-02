# Exploration Log

## MCP Setup Journey

### Step 1: Understanding MCP
- MCP = Model Context Protocol
- Tenx MCP server logs developer-AI interactions
- Non-invasive, runs in background

### Step 2: Installation
```bash
claude mcp add --transport http tenxfeedbackanalytics https://mcppulse.10academy.org/proxy -H "X-Device: linux" -H "X-Coding-Tool: claude"
```
Result: Success

### Step 3: Authentication
- Ran `/mcp` in Claude Code
- Redirected to GitHub OAuth
- Authorized TenxMCPPulse app
- Connection confirmed

## Research Notes

### Boris Cherny's Key Insights
1. Runs 5 Claudes in parallel
2. Uses Opus 4.5 with thinking for everything
3. Plan mode first, then auto-accept
4. CLAUDE.md is ~2.5k tokens at Anthropic
5. "Every correction becomes permanent context"

### Best CLAUDE.md Patterns Found
- Keep under 150-200 instructions
- Include copy-paste ready commands
- "Don't do X, use Y instead" format
- Treat as living document, not static

## Tools Explored
- Claude Code CLI
- Tenx MCP Analytics
- GitHub OAuth integration
- Web search for research
