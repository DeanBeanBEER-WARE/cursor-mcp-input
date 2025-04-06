# MCP Notion-GitHub Integration

Dieses Projekt integriert Notion und GitHub über einen MCP-Server.

## Funktionen

- Automatische Synchronisation zwischen Notion und GitHub
- Echtzeit-Updates von Issues und Pull Requests
- Notion-Datenbank-Integration
- GitHub Repository Management

## Installation

1. Klone das Repository
2. Installiere die Abhängigkeiten:
   ```bash
   npm install
   ```
3. Konfiguriere die Umgebungsvariablen in `.env`
4. Starte den MCP-Server:
   ```bash
   node index.js
   ```

## Konfiguration

Stelle sicher, dass du folgende Umgebungsvariablen in deiner `.env`-Datei hast:
- `GITHUB_TOKEN`
- `NOTION_TOKEN`
- `NOTION_DATABASE_ID`

## Lizenz

MIT