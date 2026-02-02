# TRP 1 - MCP Setup Challenge Report

## What I Did

### Task 1: MCP Setup
- Installed Claude Code CLI
- Added Tenx MCP server using:
  ```bash
  claude mcp add --transport http tenxfeedbackanalytics https://mcppulse.10academy.org/proxy -H "X-Device: linux" -H "X-Coding-Tool: claude"
  ```
- Authenticated via GitHub OAuth
- Verified connection with `/mcp` command

### Task 2: Research & Configure CLAUDE.md
- Researched Boris Cherny's (Claude Code creator) workflow
- Studied community best practices for CLAUDE.md files
- Created CLAUDE.md with:
  - Project overview and tech stack
  - Common commands (copy-paste ready)
  - Code style guidelines
  - Workflow rules (plan first, verify work)
  - "Do NOT" section with alternatives
  - Learning log for iterative improvement

## What Worked
1. **MCP Setup** - Straightforward following the documentation
2. **GitHub OAuth** - Seamless authentication flow
3. **Research approach** - Web search for Boris Cherny's practices yielded clear insights
4. **Concise CLAUDE.md** - Following the "keep it short" principle (~150-200 instructions max)

## What Didn't Work
1. **Initial confusion** - Understanding difference between MCP server and rules file took time
2. **Time pressure** - 1-hour limit made deep experimentation difficult

## Insights Gained

### How Rules Change AI Behavior
1. **Structure matters** - Clear sections help the AI find relevant instructions quickly
2. **Negative rules need alternatives** - "Don't do X" alone is less effective than "Don't do X, use Y instead"
3. **Living document concept** - CLAUDE.md should evolve with every mistake, not be static
4. **Less is more** - Concise rules are followed better than lengthy documentation

### Key Takeaways from Boris Cherny
- Start with plan mode for non-trivial tasks
- Give AI ways to verify its work (2-3x quality improvement)
- Keep CLAUDE.md in git, shared with team
- Add corrections as mistakes happen - "cost of mistake pays dividends forever"

## References
- [Boris Cherny's workflow](https://twitter-thread.com/t/2007179832300581177)
- [How Boris Uses Claude Code](https://paddo.dev/blog/how-boris-uses-claude-code/)
- [Writing a good CLAUDE.md](https://www.humanlayer.dev/blog/writing-a-good-claude-md)
