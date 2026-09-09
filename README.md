# react-utility-hooks

Small typed hooks: debounce, localStorage, media query, toggle

## Usage

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Features

- useMediaQuery SSR-safe
- useDebounce with leading/trailing options
- useLocalStorage with JSON serialization
- Tiny: no dependencies besides React

## Install

```bash
npm install
npm test
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
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
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version
