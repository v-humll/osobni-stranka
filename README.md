# Osobní stránka – Vojtěch Huml

## Media rules

| Pravidlo | Co se mění a proč |
| --- | --- |
| `@media (min-width: 40em / 60em / 80em)` | Navigace se na širším displeji přepne do řádku a karty projektů se postupně rozloží do 2 a 3 sloupců, aby bylo rozvržení čitelné bez vodorovného posuvníku. |
| `@media (prefers-color-scheme: dark)` | Přepne CSS proměnné barev na tmavé schéma s dostatečným kontrastem a upraví barvu posuvníků pomocí `color-scheme: light dark`. |
| `@media (prefers-contrast: more)` | Nastaví nejvyšší kontrast barev (úroveň AAA), zesílí okraje na 2px, podtrhne odkazy a odstraní barevný přechod na pozadí pro maximální čitelnost. |
| `@media (prefers-reduced-motion: reduce)` | Vypne plynulé rolování (`scroll-behavior: auto`) a zkrátí všechny přechody a animace, aby pohyb nezpůsoboval nevolnost. |
| `@media (prefers-reduced-transparency: reduce)` | Nahradí poloprůhledné pozadí karet a rozostření (`backdrop-filter`) plnou barvou, aby byl text vždy jasně čitelný. |
| `@media (forced-colors: active)` | Zajistí viditelné okraje karet, tabulky a navigačních odkazů i obrys fokusu pomocí systémových barev (`CanvasText`, `ButtonBorder`, `Highlight`). |
| `@media (prefers-color-scheme: dark) and (prefers-contrast: more)` | Kombinuje tmavé pozadí s nejvyšším kontrastem písma a odkazů pro uživatele, kteří vyžadují obojí současně. |
