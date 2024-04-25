## Introduction

A NextJS 14+ starter project using lcl.host to create HTTPS in local development environment

This starter kit is composed of:

- [Next.js](https://nextjs.org/) - App router
- Tailwind
- Typescript
- Prettier / Prettier-plugin-tailwind
- Husky / Lint-staged
- SVG import through [@svgr/webpack](https://www.npmjs.com/package/@svgr/webpack)

## Installation

```bash
brew install anchordotdev/tap/anchor
```

```bash
anchor lcl
```

Follow the set up process in the cli. Once directed to the setup page, follow the instructions there. You can skip step 1, as the `anchor-pki` and `next.config` file has already been updated for you.

Create `.env.local` and add your generated tokens and values from that step to that file.

Your project is now secure with HTTPS in your local dev environment!

To run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Learn More

To learn more about lcl.host and Anchor, take a look at the following resources:

- [Next.js+lcl.host Setup Guide](https://anchor.dev/blog/https-on-localhost-nextjs)
- [Anchor](https://anchor.dev)
- [Lcl.host](https://lcl.host)
- [Lcl.host / Anchor Documentation](https://anchor.dev/docs)
