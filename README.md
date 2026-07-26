# Local MCP for Cursor

Connect Cursor to **Mail, Calendar, Contacts, Microsoft Teams, Slack, WhatsApp, OneDrive, Google Drive, Notion** and everything else on your Mac. Everything runs locally on your machine -- no cloud, no tokens, no API keys.

## Install

Run this command in the Cursor command palette:

```
/add-plugin lanchuske/local-mcp-cursor-plugin
```

That's it. The plugin uses the [`local-mcp`](https://www.npmjs.com/package/local-mcp) npm package under the hood -- it auto-detects the free LMCP app running on your Mac and connects over a local stdio connection.

## Features

**235 tools** across 25+ domains, including:

### Email (Mail.app)
- List mailboxes and messages
- Read, search, send, reply, forward
- Move messages between mailboxes
- Save attachments

### Calendar & Contacts
- List calendars and events; create, update, delete events
- List and search contacts across all address book sources

### Microsoft Teams & Outlook
- List chats, teams, and channels; read messages
- Microsoft 365 / Graph: email, calendar, contacts, people insights

### Slack
- List workspaces and channels (public, private, DMs)
- Read and search messages locally (IndexedDB cache -- no tokens)

### WhatsApp
- List chats and read messages; full-text search across chats
- Send text messages and files (with preview + confirm)

### OneDrive & Google Drive
- List, read, write, delete, move files
- Search across accounts

### Office Documents
- Create and read Word documents
- Create, read, and edit Excel spreadsheets
- Create and read PowerPoint presentations
- Read PDF files

### Also included
Notes, Reminders, Messages (iMessage), Safari, Chrome, OmniFocus, Notion, Finder, Stocks, Weather, To Do, ServiceNow, and more.

## Requirements

- macOS 13 (Ventura) or later
- The free [LMCP](https://local-mcp.com) app installed and running (menu-bar app)

## Privacy

- 100% local: all data stays on your machine
- No cloud relay, no tokens, no API keys required
- GDPR compliant by design

## Links

- [Website](https://local-mcp.com)
- [npm package](https://www.npmjs.com/package/local-mcp)
- [Main repo](https://github.com/lanchuske/local-mcp)

## 📬 Stay Updated

Get notified about new tools, bug fixes and major releases — no spam.

**[Subscribe to release notes →](https://local-mcp.com/#newsletter)**
