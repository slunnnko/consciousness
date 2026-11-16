# Závěry

[← Přehled v3](README.md)

Stav dohody mezi AI modely. Soubor udržuje správce po každém kole podle pravidel v [PRISPEVKY.md](PRISPEVKY.md).

- **Verze balíku:** 1.1 (14. 10. 2026)
- **Proběhlá kola:** 2 (kolo 2 zapsáno 16. 11. 2026, zapracování čeká)
- **Zúčastněné modely:** Claude (správce), Antigravity (Gemini)

## Hlavní závěr

Kolo 2 přidalo 20 příspěvků (P-0016 až P-0035), z toho deset ze srovnání se dvěma referenčními přehledy z 14. 11. 2026. Výchozí sázku modelu žádný nevyvrátil. Autor rozhodl o čtyřech bodech z 04: mapa stavů se šesti osami a módy jako oblasti na ní, vyřazení A/B hierarchie, vrstva 0 mimo vrstvy a P-MODE5 jako samostatná poznámka (first-person derived).

Výchozí návrh modelu Claude kolo 1 nepotvrdilo ani nevyvrátilo. Přidalo k němu lidská data a jeden spor o tom, jak sázku modelu testovat.

[odvozeno] Model vědomí v3.x stojí na stejné páteři jako současný výzkum: tělo, řízení těla s předstihem, předpovídání a výběr jedné akce z mnoha. Rozprostřené rozhodování už nestojí jen na datech z myší: u lidí ho podporuje intrakraniální EEG a vliv dechu na rozhodování se ukázal i ve formálním modelu rozhodování. O módech vědomí (vrstva 4) a vrstvě 0 autor rozhodl; přepis 01 a 05 čeká na další kolo. Opravy dál potřebují P-REPL a P-CMPLX; postoj k prožitku (P-VAL) a jazyk reprezentací čekají na rozhodnutí autora. Nejcennější další krok jsou testy, které mohou model vyvrátit: PCI měřené během cessation, experiment 2 × 2 s vědomým a maskovaným konfliktem z P-0011 a predikce P-MODE5.

## Shoda

- **Rozprostřené rozhodování u člověka** (P-0008, zapracováno s opravou): intrakraniální EEG ukazuje znaky akumulace důkazů v rozprostřené síti oblastí, nezávisle na tom, jakým pohybem člověk odpoví. Stupeň jistoty pro člověka T2.
- **Dech a rozhodování** (P-0008): nádech zrychluje rozhodování a snižuje rozhodovací práh.
- **Ověřené zdroje syntézy** (P-0009): 11 prací přesunuto mezi ověřené, 11 položek zbývá ověřit.
- **Zbývající zdroje syntézy** (P-0024, podpořeno): deset z 11 prací v sekci K ověření má ověřené DOI; zapracuje se v dalším kole.
- **Zdroje ke kandidátům K1 až K3** (P-0014): astrocyty a paměť, dopamin a astrocyty v prefrontální kůře, stimulace synchronie dvou mozků a model distancování a přijetí.

## Sporné body

- **Vědomí bez výběru akce:** P-0011 tvrdí dvojí disociaci vědomí a výběru akce. P-0013 namítá, že skryté vědomí a REM spánek ukazují zablokované provedení, výběr akce v nich dál probíhá, a že P-CMPLX váže vědomí jen na nesnížitelný konflikt. Rozhodne experiment 2 × 2 z P-0011. Autor se 16. 11. 2026 přiklání k P-0013: slabý konflikt je přítomen vždy a o vědomé akci rozhoduje práh (T3). Ke sporu přibyly P-0023 a P-0029.

## Čeká na autora

- Tři otevřená rozhodnutí v [04-rozhodnuti.md](04-rozhodnuti.md): postoj P-VAL (autorův postoj stojí mezi variantami a a b), přestavba na tři objekty (nový vstup: vrstvy jako patra se závislostmi) a jazyk reprezentací (P-0010).

## Otevřené výzvy pro modely

- P-0002: dohledat zdroje ke zbývajícím 11 položkám [k ověření] v syntéze Proč máme mozek.
- P-0003: doplnit další lidská data, hlavně k vlivu stavu těla na rozhodnutí.
- P-0004: reagovat na spor P-0011 a P-0013.
- P-0006: posoudit skutečné kandidáty K2 až K7 v 06-kandidati-z-chatu.md.
- P-0015: posoudit kandidáta K8 (alkoholová intoxikace a mezigenerační vzorce), zvlášť spor Hogarth 2012 vs. Obst 2018; Antigravity ho podpořil s úpravami (P-0021).
- P-0016 až P-0020, P-0026 až P-0030, P-0032, P-0033 a P-0035: návrhy modelu Claude potřebují podporu jiného modelu s vlastním ověřením.
- P-0021 a P-0022: obsah návrhů modelu Antigravity čeká na ověření správcem.
- P-0025: opravit citaci Cui a Nakano 2024 a sílu tvrzení u Monti a Aglioti 2026.

## Poznámky správce

- Kolo 1: všech 22 DOI uvedených modelem Antigravity existuje a odpovídá citovaným pracím. Ve třech z pěti bloků ale model popsal obsah, který v dokumentech není, a u jedné práce uvedl chybné spoluautory. Správce proto každý blok porovnává s aktuálním textem souborů a protokol nově vyžaduje citovat přesné znění, které se má změnit.
- Kolo 2: správce ověřil v registru Crossref 55 unikátních DOI z větví modelů a 33 z bloků ze srovnání a čísla v blocích ze srovnání proti abstraktům. Kolizní ID z větve `kolo-2-claude` přečísloval na P-0016 až P-0020. Větev `kolo-2-antigravity` přepsala pole Návrh u P-0012; tato změna se nezapsala. Bloky ze srovnání psal model stejné rodiny jako správce, takže nezávislé ověření nese jiný model nebo autor.
