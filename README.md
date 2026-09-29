# Context Operator

Keep AI work coherent across chats, agents, and long-running projects.

**Developer:** AI Operators<br>
**Version:** 0.1.0

Context Operator is a self-contained plugin with six workflows:

- **Context:** build durable project context.
- **Task:** define a significant assignment.
- **Update:** reconcile new decisions and constraints.
- **Compress:** turn long history into concise current state.
- **Handoff:** transfer work to another chat or agent.
- **Review:** check an output against its requirements.

No external MCP server, API, or Context Operator account is required.

Context Operator is free to install and use for personal, professional, and internal business work. Commercial use of your outputs is permitted. Redistribution, resale, repackaging, sublicensing, and commercial distribution of derivative versions are prohibited. See [LICENSE](LICENSE) for full terms.

## Verified surfaces

Codex CLI remote installation and behavior, ChatGPT desktop loading and behavior, Claude Code direct/local behavior, and Claude Code remote installation and six-skill discovery have been tested. Execution specifically from the Claude Code remote-installed plugin remains unverified. In a fresh context-free Claude Code session, Task may ask more questions than intended before producing a useful partial specification. ChatGPT web/mobile, Claude.ai, Claude desktop/app, and Cowork have not been verified.

## Install in Codex

```sh
codex plugin marketplace add The-AI-Operators-Club/context-operator
codex plugin add ai-operator-context-system@ai-operator-context-system
```

Start a new Codex session. The plugin is also available through the **AI Operators** marketplace in `/plugins`.

## Install in ChatGPT desktop

Add the repository marketplace with the Codex command above, then restart ChatGPT desktop. In the Plugins Directory, select **AI Operators**, install **Context Operator**, and start a new chat. Availability can depend on your account and workspace settings.

## Install in Claude Code

```sh
claude plugin marketplace add The-AI-Operators-Club/context-operator
claude plugin install ai-operator-context-system@ai-operator-context-system
```

Start a new Claude Code session after installation. The plugin contains Context, Task, Update, Compress, Handoff, and Review.

## Status

This repository distributes a generated package. The development repository is the source of truth for changes. Public-directory metadata remains under review; see [release notes](RELEASE-NOTES.md).
