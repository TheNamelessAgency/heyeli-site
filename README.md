# heyELi Static Landing (Vercel-ready)

This is a zero-dependency static site for **heyELi**. Deploy to Vercel for free.

## Quick Deploy (no CLI)
1) Create a GitHub repo named `heyeli-site`.
2) Upload these files (or drag the whole folder).
3) Go to https://vercel.com/new → **Import Git Repository** → select `heyeli-site` → Deploy.
4) In Vercel: **Settings → Domains → Add** `heyeli.app`.
5) Copy the DNS records Vercel shows into your domain registrar.
6) Done. Your site is live on `https://heyeli.app` when DNS propagates.

## Optional: Vercel CLI
```bash
npm i -g vercel
vercel  # first deploy (accept defaults)
vercel --prod  # push to production URL
```

## Customize
- Replace the Google Form embed in `index.html` with your actual beta form.
- Swap `/assets/halo-e.svg` with your brand mark.
- Update copy in sections as needed.

