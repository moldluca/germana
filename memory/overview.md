---
name: Germana flashcards — overview
description: Site static cu flashcard-uri de vocabular germană (Luca, școală), live pe germana.moldluca.tech
type: project
---

- **Live:** https://germana.moldluca.tech — GitHub Pages din repo `moldluca/germana` (branch main, root), fără build.
- **DNS:** Cloudflare CNAME `germana` → `moldluca.github.io`, DNS-only (proxied off), creat cu tokenul DNS moldluca.tech din vault. Același tipar ca [[arbori.moldluca.tech]].
- **Conținut:** `index.html` singur; vocabularul e array-ul `V` din script. Prima listă: „Soziale Netzwerke” (22 cuvinte, din fișa de lucru, 2026-10-22).
- Pentru o listă nouă: adaugi perechi în `V` (sau o pagină nouă), commit + push; Pages redeployează singur.
