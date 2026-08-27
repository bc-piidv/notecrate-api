# notecrate-api

Small bookmark service with search and tags

## How to use

```bash
curl -X POST localhost:3000/api/bookmarks \
  -H 'content-type: application/json' \
  -d '{"url": "https://example.com", "tags": ["reading"]}'
```

## Getting started

```bash
npm install
npm run dev
```

## Highlights

- In-memory store with optional JSON persistence
- Request validation helpers, no framework magic
- REST endpoints: list / create / delete / search
- Ready for Render/Fly deploy with PORT env
- Morgan logging and centralized error handler

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── src/
│   ├── config.js
│   ├── index.js
│   └── store.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
npm test
```

## License

MIT licensed, see LICENSE.
