# 03 Hala — logo „Míček v názvu“

Návrh loga Tenisové akademie Louny pro variantu webu **03 Hala** (tmavý moderní luxus). Stav: náhled konceptu, ne tisková data.

## Myšlenka

Písmeno O ve slově LOUNY nahrazuje plný tenisový míček, takže název a sport jsou v jednom slově a vedle už není potřeba další symbol. Míček je postavený z čisté geometrie: kruh a dva švy jako oblouky kolmé k obrysu. Švy jsou průhledné, takže znak funguje na světlém i tmavém pozadí a v jedné barvě. Elektricky modrý míček s jedinou červenou čočkou je ve tmě haly jediné světlo: barva je soustředěná do jednoho bodu, zbytek je klidná tmavá modrá nebo bílá. Samotný míček slouží jako znak, favicon i střed odznaku Partnerský klub.

## Soubory

| Soubor | Použití |
|---|---|
| `znak.svg` | samotný míček (barevný, švy průhledné) |
| `logo-vodorovne.svg` | jednořádkové logo pro světlé pozadí (hlavička webu) |
| `logo-vodorovne-negativ.svg` | totéž pro tmavé pozadí; bílé písmo, na bílém není vidět |
| `logo-jednobarevne.svg` | jednobarevné logo `#0D1B45`; bílou verzi získáte přebarvením všech výplní na `#FFFFFF` |
| `favicon.svg` | zjednodušený znak se silnějšími švy na dlaždici `#0D1B45`, čitelný i v 16 px |
| `partnersky-klub.svg` | Logo II, odznak „Partnerský klub · Akademie Louny“ pro světlé pozadí |
| `nahled.png` | prezentační list 1600 × 1000 px |
| `logo-blok.svg`, `logo-blok-negativ.svg` | navíc: bloková verze (AKADEMIE nad LOUNY) pro trička, mikiny a úvod webu |
| `partnersky-klub-negativ.svg` | navíc: odznak pro tmavé pozadí (bílý okraj) |

## Barvy

| Barva | HEX | Použití |
|---|---|---|
| tmavě modrá | `#0D1B45` | písmo, jednobarevná verze, odznak |
| elektrická modrá | `#2F6BFF` | míček |
| červená | `#FF3B4E` | čočka míčku a tečky v odznaku |
| bílá | `#FFFFFF` | negativ, text odznaku |

Pozadí webu Hala je `#070F2B`. V logu tato barva není.

## Písmo

**Jost** (Owen Earl, indestructible type*), verze 3.710, z Google Fonts (`google/fonts`, složka `ofl/jost`). Licence: **SIL Open Font License 1.1**, která dovoluje použít písmo v logu. Použité váhy jsou 600 až 660. Text je převedený do křivek, takže soubory SVG žádné písmo nepotřebují.

## Poznámky

- **Nejmenší detaily.** Žádné vlasové linky: každý tah a každá mezera mají aspoň 1,2 % šířky loga. Ověřeno na rastru v Chromiu u všech souborů. Pod hranici jdou jen ostré špičky písmen (N, M, A). Vnitřní trojúhelník písmene A je přesně na hranici (1,17–1,2 %). Šev míčku má 31 % poloměru.
- **Odznak.** Čárka nad Ý v PARTNERSKÝ je mírně zvednutá a zesílená, aby ji neslil malý tisk ani výšivka.
- **Tisk a výšivka.** Barvy jsou RGB. Odstíny Pantone a CMYK je potřeba určit až při přípravě tiskových podkladů; elektrická modrá a červená budou v CMYK méně syté. Pro výšivku orientačně počítejte s nejmenším detailem kolem 1 mm:
  - logo (vodorovné i blokové) od šířky zhruba 85 mm,
  - menší aplikace (rukáv, kšilt) jen znak, míček od zhruba 12 mm.
  
  Tyto hodnoty je potřeba ověřit s vyšívárnou.
- **Slabá místa.** Míček se dvěma švy je známý piktogram. Jedinečnost stojí na spojení s názvem, které dává ozvláštnění O a červená čočka; samotný znak tolik nevynikne. Jednořádkové logo je dlouhé (asi 12 : 1), proto je na trička vhodnější bloková verze. Jost vychází z Futury a je hodně rozšířený.
