# ai-e2e-gen

[![npm version](https://img.shields.io/npm/v/ai-e2e-gen.svg)](https://www.npmjs.com/package/ai-e2e-gen)
[![npm downloads](https://img.shields.io/npm/dm/ai-e2e-gen.svg)](https://www.npmjs.com/package/ai-e2e-gen)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-e2e-gen)](https://github.com/lxgic-studios/ai-e2e-gen/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate Playwright (or Cypress) e2e tests from a URL, component file, or description.

## Install

```bash
npm install -g ai-e2e-gen
```

## Usage

```bash
npx ai-e2e-gen https://myapp.com
# Generates Playwright tests for the page

npx ai-e2e-gen ./src/LoginForm.tsx -o tests/login.spec.ts
# Generates tests from component, writes to file

npx ai-e2e-gen "shopping cart checkout flow"
# Generates tests from description
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## Options

- `-o, --output` - Write tests to a file
- `-f, --framework` - playwright or cypress (default: playwright)

## License

MIT
