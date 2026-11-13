<p align="center"><img src="https://raw.githubusercontent.com/openses-email/.github/main/profile/logo.png" width="80" alt="OpenSES logo"></p>

# OpenSES

**Open-source email on your own Amazon SES.**

OpenSES adds what Amazon SES leaves out: a send API, templates, signed webhooks, a searchable email log, suppressions, a shared inbox for receiving and replying, contacts with topics and segments, broadcasts with one-click unsubscribe, and drip or sales sequences. Email always goes out through your own AWS account, so you pay Amazon's price ($0.10 per 1,000 emails) and the domain reputation stays yours.

[Website](https://openses.email) · [Docs](https://openses.email/docs) · [Dashboard](https://app.openses.email) · [Self-host](https://openses.email/self-host)

## Use OpenSES from your AI tools and automations

| Repository | What it is |
| --- | --- |
| [mcp-server](https://github.com/openses-email/mcp-server) | The MCP server for Claude, ChatGPT, Cursor and other assistants: remote at `https://api.openses.email/mcp`, or `npx -y openses-mcp` and a Claude Desktop extension |
| [plugin](https://github.com/openses-email/plugin) | The Claude plugin: MCP server, skill, and `/openses:inbox`, `/openses:delivery`, `/openses:health` |
| [agent-skill](https://github.com/openses-email/agent-skill) | The agent skill: `npx skills add openses-email/agent-skill` |
| [n8n-nodes-openses](https://github.com/openses-email/n8n-nodes-openses) | n8n nodes for sending, contacts, sequences, the inbox, and a trigger for delivery and inbound-mail events |

## Things to ask your assistant

> What came into support@ today? Draft replies for the billing questions.

> Did my email to dana@example.com arrive? If not, why?

> Add jo@example.com to the newsletter and start the onboarding sequence.

## Security

Report vulnerabilities privately to security@openses.email. Never post API keys, tokens or customer email in an issue.
