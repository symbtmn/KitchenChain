# KitchenChain

Restaurant ingredient traceability frontend — SE-2503 student project.

**Live website:** https://symbtmn.github.io/KitchenChain/  
**Source code:** https://github.com/symbtmn/KitchenChain

GitHub Pages builds and deploys automatically from the `main` branch.

## Features
- Ingredient deliveries and supplier directory
- Search and filter batches
- Batch origin and delivery timeline
- Accept or reject after inspection
- Save demo decisions in the browser
- Export batch records as CSV
- Responsive cream and burgundy interface

## Run locally
Requires Node.js 22 or later.

```bash
npm install
npm run dev
```

Build with `npm run build`; preview with `npm run preview`.

## Demo walkthrough
Open KC-2401, confirm the inspection, and accept the delivery. KC-2403 shows a flagged delivery that can be rejected with a reason.

## Technology
React, TypeScript, Vite, CSS, Lucide icons.

## Limitations
Suppliers and records are sample data. There is no backend, wallet, live blockchain connection, or camera QR scanner. Decisions remain in this browser. The food illustration was AI-generated. This frontend was developed with AI assistance.

## Team
Symbat Abdirakhman and Akerke Zulpybek — SE-2503.
