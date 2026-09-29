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

## Verified surfaces

Codex CLI, ChatGPT desktop, and Claude Code have been tested. In a fresh Claude Code session without project context, Task may ask more questions than intended before producing a partial specification. ChatGPT web/mobile, Claude.ai, Claude desktop/app, and Cowork have not been verified.

## Install in Codex

```sh
codex plugin marketplace add The-AI-Operators-Club/context-operator
```

Start Codex, open `/plugins`, select the **AI Operators** marketplace, install **Context Operator**, then start a new session.

## Install in ChatGPT desktop

Add the repository marketplace with the Codex command above, then restart ChatGPT desktop. In the Plugins Directory, select **AI Operators**, install **Context Operator**, and start a new chat. Availability can depend on your account and workspace settings.

## Install in Claude Code

```sh
claude plugin marketplace add The-AI-Operators-Club/context-operator
claude plugin install ai-operator-context-system@ai-operator-context-system
```

Start a new Claude Code session after installation. The plugin contains Context, Task, Update, Compress, Handoff, and Review.

## Status

This repository distributes a generated package. The license and other publication terms remain unresolved; see [release notes](RELEASE-NOTES.md). The development repository is the source of truth for changes.
