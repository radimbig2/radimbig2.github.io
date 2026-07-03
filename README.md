# Radim Knowledge Base

Personal digital garden and portfolio knowledge base built with Quartz 5.

Live site:

https://radimbig2.github.io

## Local Development

Requirements:

- Node 22+
- npm 10.9.2+

Install dependencies:

```sh
npm ci
```

Install Quartz plugins:

```sh
npx quartz plugin install
```

Build the static site:

```sh
npx quartz build
```

Preview locally:

```sh
npx quartz build --serve
```

The local preview runs at `http://localhost:8080`.

## Content

All public pages live in `content/`.

Images and other static assets should be placed under `content/assets/`.
