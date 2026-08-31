# Azizi Florence — Novera Real Estate Landing Page

Pre-launch landing page for Azizi Florence (Sharjah), built for Novera Real Estate's lead-gen campaign.

## Structure
```
index.html          — the full page (single file, no build step)
assets/img/          — all photography (real Azizi Florence renders from the developer brochure)
assets/fonts/        — self-hosted EB Garamond + Montserrat (woff2)
```

## Deploy on Vercel
This is a plain static site — no build command needed.

1. Import this repo in Vercel.
2. Framework preset: **Other** (or "No framework").
3. Build command: leave blank.
4. Output directory: leave as root (`.`).
5. Deploy.

## Lead capture
The enquiry form currently opens a pre-filled WhatsApp chat on submit (no backend required).
To route leads into **DealOS** instead, replace the `fetch`/`window.open` call in the
`<script>` block at the bottom of `index.html` with a POST to the DealOS webhook/API endpoint,
once that's available from whoever manages the DealOS account.

## Key dates (update if these change)
- EOI closes: **9 September**
- Pre-launch event: **10 September**
- Launch price: **AED 850/sq. ft.**, from **AED 1.89M**

## Contact
Novera Real Estate — +971 58 542 4430 — noverarealty.ae
