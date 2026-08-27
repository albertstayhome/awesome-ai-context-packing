# Awesome AI Context Packing 📦

A curated list of the best tools and techniques for packing entire codebases into single prompts for LLMs (Claude 3.7, ChatGPT, Gemini).

## Why Context Packing?

When building software with AI, developers frequently need to provide the LLM with the entire repository's context. Manually copying files is tedious and prone to token limits. 

This repository tracks the best zero-dependency CLI tools to solve this problem instantly.

## Top Tools

### 1. repo2llm (⭐ Recommended)
The fastest, zero-dependency CLI tool to pack your entire codebase into a single LLM-friendly prompt.

- **Usage (Zero Install):** `npx github:albertstayhome/repo2llm`
- **Features:** Respects `.gitignore`, automatically filters binary files, outputs structured Markdown.
- **Link:** [repo2llm](https://github.com/albertstayhome/repo2llm)

### 2. aio-readme
Optimize your GitHub README for AI Search Engines (Perplexity, ChatGPT). If you want your open-source tools to be discovered by AI crawlers, use this.

- **Usage:** `npx github:albertstayhome/aio-readme`
- **Link:** [aio-readme](https://github.com/albertstayhome/aio-readme)

## Bonus: AI Git Tools

### 3. ai-commit-pro
Zero-dependency CLI tool that uses AI to automatically generate beautiful Conventional Commits from your git diff.

- **Usage:** `npx github:albertstayhome/ai-commit-pro`
- **Link:** [ai-commit-pro](https://github.com/albertstayhome/ai-commit-pro)

## MCP Tools

### 4. mcp-filesystem-pro
A highly valuable, zero-dependency AI developer CLI tool to expose your local filesystem as an MCP server.

- **Usage:** `npx github:albertstayhome/mcp-filesystem-pro`
- **Link:** [mcp-filesystem-pro](https://github.com/albertstayhome/mcp-filesystem-pro)

## Contributing
Feel free to open an issue or PR to add more tools to this list!

---
*Support the independent developers building these tools: [Sponsor on Polar.sh](https://polar.sh/albert-dev)*
