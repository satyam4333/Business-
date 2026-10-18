# JERVISH Business Suite — Free Self-Hosted Edition

A Refrens-inspired, local-first business management app. It is an independent implementation and does not use Refrens code, branding, or private APIs.

## Included
- Dashboard
- GST-ready invoice builder with line items, HSN/SAC and GST
- Quotations + convert quotation to invoice
- Client management
- Product/item catalogue
- Payment recording and outstanding calculation
- Expense/purchase tracking
- Business settings
- Print / Save as PDF through browser print
- JSON backup and restore
- Responsive desktop/mobile layout
- PWA manifest
- No paid API, no database subscription, no login required

## Deploy
This is a static site. Upload `index.html` and `manifest.json` to any static hosting provider such as GitHub Pages, Netlify, Vercel, Cloudflare Pages, or your own server.

No build command is required.

## Important limitation
Because this version is intentionally static and free, data is stored in the browser's localStorage. It is not a cloud multi-user SaaS. Clearing browser data removes the local data, so use Backup / Restore regularly.

It does not include proprietary/regulated integrations such as Refrens' private backend, bank feeds, WhatsApp/email delivery infrastructure, payment gateway settlement, GSTN e-invoice API credentials, e-way bill API credentials, or AI OCR backend. Those require external services/accounts.

## Recommended next upgrade
If you want a true cloud SaaS with login, PostgreSQL, multi-user access, file storage, email/WhatsApp, and server-side PDF generation, this same UI can be moved to a React/Next.js + Supabase architecture.
