# AREDO Kalkulátor

Webová kalkulačka pre AREDO ohýbané dielce. Single-file HTML aplikácia — všetok kód (HTML, CSS, JS) je v jednom súbore. Žiadny build, žiadne závislosti (Three.js a jsPDF sa načítavajú z CDN).

- **Živá verzia:** https://aredo-tools.github.io/aredo-kalkulator/
- **Hlavný súbor:** `lenka_4.0.html`

## Štruktúra
| Súbor / priečinok | Popis |
|---|---|
| `index.html` | Presmerovanie na hlavnú appku (aby root adresa otvorila kalkulačku) |
| `lenka_4.0.html` | **Hlavná aplikácia** — TYP1/TYP2 kalkulačka, 3D model, PDF export, sklo, lamely, nadväznosť panelov |
| `archiv/` | Staršie verzie (lenka 3.0, kalkulačka 4.1) |
| `.nojekyll` | Vypína Jekyll — Pages servujú súbory tak ako sú |

## Nasadenie
GitHub Pages z branchu `main`. Po `git push` sa živá verzia aktualizuje automaticky (~1 min).
