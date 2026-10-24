# Bugaa's website

Cheesecake cloud-kitchen site. Orders go to WhatsApp; no online payments yet.

## Edit settings
Open `index.html` and find the **Settings** block near the bottom:

- `WHATSAPP_NUMBER` — digits only, starting with `20` and without the leading 0 (010 1234 5678 → `201012345678`)
- `PRODUCTS` — names, sizes, prices (EGP) and descriptions
- `FLAVOURS` — the flavour list and each flavour's photo file
- `perPiece` (slices) — sold one by one, `price` is per slice
- `sizes` (bites) — the box sizes, how many bites each holds, and their prices

Images live in `images/`. Flavour photos go in `images/flavours/` (see the README there). Replace a file with the same name to swap a photo.

Hosted on GitHub Pages from the `main` branch.
