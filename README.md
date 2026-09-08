# habitmesh

Small Vue 3 side project: track daily habits as a heatmap grid

Built for my own use; public in case it helps someone.

## How to use

```bash
# open http://localhost:5173
# click a cell to toggle that day
```

## Highlights

- Composition API + script setup
- GitHub-style contribution grid per habit
- State persisted to localStorage
- Vite dev setup with hot reload

## Installation

```bash
npm install
npm run dev
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── App.vue
│   ├── main.js
│   └── store.js
├── .editorconfig
├── .gitignore
├── CODE_OF_CONDUCT.md
├── LICENSE
├── SECURITY.md
├── index.html
├── package.json
└── vite.config.js
```

## Development

```bash
npm install
```

## Why

Needed this for myself; figured others might too.

## License

MIT. Do whatever you want.
