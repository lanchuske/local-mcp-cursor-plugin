# Local MCP for Cursor

Connect Cursor to **Mail, Calendar, Contacts, Microsoft Teams, Slack, WhatsApp & OneDrive** on macOS and Windows. Everything runs locally on your machine -- no cloud, no tokens, no API keys.

## Install

Run this command in the Cursor command palette:

```
/add-plugin lanchuske/local-mcp-cursor-plugin
```

That's it. The plugin uses the [`local-mcp`](https://www.npmjs.com/package/local-mcp) npm package under the hood.

## Features

**189 tools** across 18 categories:

### Email (Mail.app)
- List mailboxes and messages
- Read, search, send, reply, forward
- Move messages between mailboxes
- Save attachments

### Calendar
- List calendars and events
- Create, update, delete events

### Contacts
- List and search contacts
- Access all address book sources

### Microsoft Teams
- List chats and read messages
- List teams and channels
- Read channel messages

### Slack
- List workspaces and channels (public, private, DMs)
- Read and search messages locally (IndexedDB cache — no tokens)

### WhatsApp
- List chats and read messages
- Full-text search across chats
- Send text messages and files (with preview + confirm)
- ⚠️ Uses the unofficial [Wacli](https://github.com/steipete/wacli) client — requires QR-code sign-in; accounts may be restricted for ToS violations

### OneDrive
- List, read, write, delete, move files
- Search across OneDrive accounts

### Office Documents
- Create and read Word documents
- Create, read, and edit Excel spreadsheets
- Create and read PowerPoint presentations
- Read PDF files

### NordVPN
- Check connection status
- Recommend servers by country/specialty
- Diagnose install and protocols

## Privacy

- 100% local: all data stays on your machine
- No cloud relay, no tokens, no API keys required
- GDPR compliant by design
- Works offline (except Teams and OneDrive which need their local caches)

## Links

- [Website](https://local-mcp.com)
- [npm package](https://www.npmjs.com/package/local-mcp)
- [Main repo](https://github.com/lanchuske/office-mcp)

## 📬 Stay Updated

Get notified about new tools, bug fixes and major releases — no spam.

**[Subscribe to release notes →](https://local-mcp.com/#newsletter)**
