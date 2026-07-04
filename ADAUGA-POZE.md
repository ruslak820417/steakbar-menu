# Cum adaugi pozele TALE (STEAK BAR)

1. Pune poza produsului ca `images/<ID>.jpg` (ID-ul e din `menu.json`, ex: Coca-Cola 0.33L = 22).
2. Deschide `images/manifest.json` și pune `"<ID>": "<ID>.jpg"` (dacă era `null`).
3. Publică: `git add -A && git commit -m "poze proprii" && git push`
   → meniul public se actualizează în ~30s la https://ruslak820417.github.io/steakbar-menu/

## Schimbi un preț / produs
Editează `menu.json` → `git add -A && git commit -m "update preturi" && git push`.
