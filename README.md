# KitchenChain

Restaurant ingredient traceability frontend — SE-2503 student project.

**Live demo:** https://kitchenchain-symbat-demo.symbat-nurlankyzy8.chatgpt.site

## Features
- Ingredient delivery list and supplier directory
- Search and filter batches
- Batch origin and delivery timeline
- Accept or reject a delivery after inspection
- Persist demo decisions in localStorage
- Export batch records as CSV
- Responsive cream and burgundy interface

## Run locally
Requires Node.js 22 or later.

```bash
npm install
npm run dev
```

Production build: `npm run build`. Preview: `npm run preview`.

## Demo walkthrough
Open KC-2401, confirm the inspection, and accept the delivery. KC-2403 illustrates a flagged delivery and can be rejected with a written reason.

## Technology
React, TypeScript, Vite, CSS, Lucide icons.

## Limitations
All suppliers and records are sample data. There is no backend, wallet, live blockchain connection, or camera QR scanner. Decisions remain in the current browser. The food illustration was AI-generated. This frontend was developed with AI assistance.

## Team
Symbat Abdirakhman and Akerke Zulpybek — SE-2503.
