# hookjar

A handful of React hooks I keep copy-pasting between projects

Small but I use it weekly.

## Getting started

```bash
npm install
npm test
```

## Features

- useDebounce with leading/trailing options
- Tiny: no dependencies besides React
- useLocalStorage with JSON serialization
- useMediaQuery SSR-safe

## Usage

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
└── package.json
```

## Development

```bash
npm install
```

## License

MIT licensed, see LICENSE.
