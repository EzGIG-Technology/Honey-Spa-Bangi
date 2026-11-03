# Honey Spa Bangi — website demo

Static demo website for Honey Spa Bangi (Bangi Sentral), prepared by EzGIG Technology.

## Structure
- `index.html` — the whole site (Home, Treatments, Promotions, Packages, Salon, Contact via `#hash` pages)
- `img/` — photos and hero videos (frames from @honeyspabangi)
- `vercel.json` — caching headers

## Deploy on Vercel
1. Vercel → **Add New… → Project** → import `EzGIG-Technology/Honey-Spa-Bangi`.
2. Framework preset: **Other**. Leave Build Command and Output Directory empty (root `./`).
3. **Deploy.**

## Preview locally
```
npx serve .
```

## Notes
- WhatsApp booking links go to +60 12-244 5415 with a pre-filled message tagged “(via website)”.
- `noindex` is set in `index.html` while this is a demo. Remove it before going live.
