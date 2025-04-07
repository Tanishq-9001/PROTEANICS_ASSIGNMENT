This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Part 1: Editor Setup
Uses @tiptap/starter-kit for basic rich-text editing functionality.
Supports paragraphs, headings, lists, blockquotes, and more.
Tailwind CSS used for UI styling.

## Part 2: Callout Node Component
A custom callout block with the following capabilities:
Callout Types:
information
best-practice
warning
error
Features:
Add callouts using the shortcut: <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd>
Slash command support: Type /callout in the editor
Change type dynamically via UI
Nested callouts are fully supported
Styled according to type

## Part 3: AI Inline Edits (Design Doc)
Key Components:
Text selection triggers a prompt modal
Instruction input sent to an LLM via API
Render AI output with diff using ProseMirror decorations
Users can accept or reject inline changes
Maintains compatibility with custom nodes (e.g., callouts)

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
