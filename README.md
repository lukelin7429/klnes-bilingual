# KangLang Elementary — moved 🧳

This repo previously served the KangLang Elementary (槺榔國小) bilingual site at
**klnes.taiwan-bilingual.org**.

**The site has moved** to the Taiwan Bilingual hub:

➡️ **https://taiwan-bilingual.org/taichung/kles/**

The canonical source now lives in the [`taiwan-bilingual`](https://github.com/lukelin7429/taiwan-bilingual)
repo under `taichung/kles/`. Future edits to the KangLang site should be made there.

This repo is kept only as a **redirector** so the old address keeps working:

- `index.html` — a friendly "we've moved" screen (auto-redirects to the new home).
- `404.html` — forwards any old deep link to the matching page at the new address
  (e.g. `…/news/kiwanis-gift/` → `…/taichung/kles/news/kiwanis-gift/`).

The `CNAME` (`klnes.taiwan-bilingual.org`) stays so the old subdomain keeps resolving
to this redirector.

Built by [My Culture Connect 人師教育協會](https://www.mycultureconnect.org/) · provided free of charge.
