# Heidi Dang

**Building AI-native developer tools that turn ambitious coding workflows into reliable, observable systems.**

I'm a software engineer and product builder working on agent orchestration, Model Context Protocol (MCP) integrations, developer runtimes, and production infrastructure. I care about the part that comes *after* the demo: permissions, execution boundaries, recovery, verification, and a UI people actually want to use.

**New here? Start with [Heidi CLI](https://github.com/heidi-dang/heidi-cli) or [FlowDeck](https://github.com/heidi-dang/FlowDeck).** If you're building coding agents, MCP servers, or developer infrastructure, [follow this profile](https://github.com/heidi-dang) for the projects and engineering work behind them.

## Start here

| Project | Why you might care | Explore |
| --- | --- | --- |
| **[Heidi CLI](https://github.com/heidi-dang/heidi-cli)** | An integrated ChatGPT MCP, CPTR execution, Live Workbench, and native repository-intelligence stack | [Overview and setup](https://github.com/heidi-dang/heidi-cli#readme) |
| **[FlowDeck](https://github.com/heidi-dang/FlowDeck)** | Agent orchestration for OpenCode, with task routing, specialist coordination, repository intelligence, and evidence-based verification | [Architecture and setup](https://github.com/heidi-dang/FlowDeck#readme) |
| **[ChatGPT Computer Plugin](https://github.com/heidi-dang/chatgpt-computer-plugin)** | A thin MCP adapter connecting ChatGPT to the CPTR execution backend | [MCP integration](https://github.com/heidi-dang/chatgpt-computer-plugin#readme) |
| **[CPTR Computer](https://github.com/heidi-dang/computer)** | Execution infrastructure for workspace, terminal, Git, browser, and automation workflows | [Backend repository](https://github.com/heidi-dang/computer#readme) |
| **[superfast-mcp](https://github.com/heidi-dang/superfast-mcp)** | A Go MCP server with bounded filesystem and Git tools, shell execution, and HTTP/stdio transports | [Build and run](https://github.com/heidi-dang/superfast-mcp#readme) |
| **[heidi-kernel](https://github.com/heidi-dang/heidi-kernel)** | A C++23 runtime daemon focused on scheduling, backpressure, and shutdown correctness | [Quickstart](https://github.com/heidi-dang/heidi-kernel#readme) |

## What makes this work interesting

Most coding-agent demos stop at “the model can call a tool.” The harder problems are turning that into dependable software:

- **Controlled execution:** workspace isolation, explicit authority, permissions, and recovery paths.
- **Agent orchestration:** bounded parallelism, task dependencies, retries, and terminal-state correctness.
- **Repository intelligence:** structure-aware code navigation, dependency and change-impact analysis, and verification planning.
- **Developer experience:** fast workflows, useful diagnostics, and responsive terminal/browser interfaces.
- **Production engineering:** tests, observable state, repeatable deployments, and security boundaries.

These are engineering goals and design areas; individual projects have their own implementation status and limitations documented in their repositories.

## How the projects fit together

```text
ChatGPT
   └─ ChatGPT Computer Plugin (MCP adapter)
        └─ CPTR Computer (execution and state)
             └─ workspace · terminal · Git · browser · verification

Heidi CLI
   └─ integrated packaging and lifecycle for the CPTR stack

OpenCode
   └─ FlowDeck (routing, orchestration, verification)
        └─ repository intelligence and specialist workflows
```

## Work with me

- **Try a project:** pick one above and follow its README. Reproducible feedback and bug reports are especially valuable.
- **Contribute:** use the issues and pull requests in the relevant repository; include environment details and a minimal reproduction.
- **Follow the work:** [follow @heidi-dang](https://github.com/heidi-dang) to find upcoming releases, architecture changes, and new open-source experiments.

**Stack:** TypeScript · Python · Rust · C++ · Go · Node.js · MCP · LLM agents · systems engineering

*Building tools worth depending on, not just tools worth demoing.*
