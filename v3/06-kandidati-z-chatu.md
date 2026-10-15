# Kandidáti na v3.2 z chatů projektu

[← Přehled v3](README.md)

Návrhy a kritiky, které vznikly v chatech projektu po vydání v3.1. Žádný z nich zatím není součástí modelu; každý čeká na posouzení. Literatura uvedená u kandidátů pochází z těchto chatů a před integrací je potřeba ji ověřit [k ověření]. Zdroje ověřené v kole 1 (verze 1.1) jsou označené [ověřeno].

## K1. Astrocyty jako implementační substrát pro doplňování vzorců (chat 11. 10. 2026)

- **Návrh:** astrocyty mohou seskupovat synaptická spojení do vybavitelných celků, a tím podporovat doplňování vzorců (pattern completion) uvnitř jedné domény. Literatura popisuje vápníkové „vodicí šablony“; jeden lidský hipokampální astrocyt kontaktuje řádově až dva miliony synapsí [k ověření].
- **Ověřené opory:** u myši se po učení aktivuje skupina astrocytů v hipokampu, úzce spjatá s neurony paměťové stopy, a ovlivňuje vybavení paměti [ověřeno] (Williamson a kol. 2025, https://doi.org/10.1038/s41586-024-08170-w). Lidské protoplazmatické astrocyty v neokortexu mají asi 2,6krát větší průměr a desetkrát víc hlavních výběžků než hlodavčí [ověřeno] (Oberheim a kol. 2009, https://doi.org/10.1523/JNEUROSCI.4707-08.2009).
- **Rozlišení podle Marrových úrovní:** astrocyty jsou kandidát na implementační substrát ukládání a doplňování v rámci domény. Přenos analogií napříč doménami vyžaduje vyšší relační operace, o kterých astrocytární literatura nemluví.
- **Směr vlivu dopaminu:** dopamin spouští rychlé vápníkové signály astrocytů v prefrontální kůře myši, a to přes α1-adrenergní receptory [ověřeno] (Pittolo a kol. 2022, https://doi.org/10.1016/j.celrep.2022.111426). Nižší dopamin by tuto aktivitu tedy spíš snižoval [odvozeno].
- **Kam patří:** L1 (implementace predikce a paměti) a L5.
- **Stupeň jistoty:** T2–T3.

## K2. Návrat mezi-organismální synchronizace (chat 11. 10. 2026; kandidát z 2. 8. 2026)

- **Mezera:** v2.3 měla celou vrstvu „Inter-organismal synchronization“ (attachment, taxonomie kanálů, zrcadlení); v3.x ji vypustila bez náhrady.
- **Co říká výzkum podle rešerše v chatu:** hyperscanning a vazba mluvčí–posluchač (Hasson), biobehaviorální synchronie (Feldman), prosociální účinek pohybové synchronie v metaanalýze (Hedges g ≈ 0,48) [k ověření]. Hlavní metodická slabina: synchronie může být artefakt společného vstupu; jako silný kauzální doklad chat uvádí stimulaci dvou mozků naráz: stimulace 20 Hz ve fázi nad levou motorickou kůrou zlepšila u dvojic synchronii pohybů oproti stimulaci v protifázi a placebu [ověřeno] (Novembre a kol. 2017, https://doi.org/10.1093/scan/nsw172). Že je to jediný takový doklad, zůstává k ověření.
- **Návrh:** vrátit synchronizaci jako rozšíření L5 v podobě sdílených generativních modelů (prediktivní zpracování mezi dvěma mozky), s predikcemi z kandidáta z 2. 8. 2026, například že se synchronizace fázově posouvá podle nabuzení [k ověření]. Pozor na kolizi názvu: „L5“ v původním kandidátu znamená vrstvu 5 z v2.3.
- **Stupeň jistoty:** T2 pro existenci synchronie, T3 pro její roli ve vědomí.

## K3. Hudba jako sdílený afekt (chat 13. 10. 2026)

- **Návrh:** hudba plní tři funkce: (1) sdílení emočního stavu, tedy emoční nákaza (Juslin & Västfjäll) a „social surrogacy“ (Derrick, Gabriel & Hugenberg); (2) přetavení emoce do formy při tvorbě; (3) zpřístupnění a zpracování uloženého materiálu, tedy paměť závislá na náladě (Bower 1981) a model distancování a přijetí (Menninghaus a kol. 2017). Model distancování a přijetí je ověřený [ověřeno] (https://doi.org/10.1017/S0140525X17000309), ostatní zdroje v tomto bodu zůstávají [k ověření].
- **Oprava formulace:** paměťové stopy jsou v mozku a tělo se aktivuje až při vybavení; „emoce uložené v těle“ je metafora.
- **Testovatelná predikce:** poslech je levný výstup, který vybije napětí a sníží motivaci k dražší tvorbě; odklad poslechu by měl tvorbu zvýšit. Riziko: u sklonu k ruminaci může smutná hudba stav zhoršovat.
- **Kam patří:** L3 a Theory A (vtělená allostatická afektivní kognice) z návrhu ze 4. 7. 2026.
- **Stupeň jistoty:** T2 pro funkce 1 a 3, T3 pro predikci.

## K4. Adversariální review z 11. 10. 2026 (verdikt 5,5/10)

- **Radikální enaktivismus (Hutto & Myin):** strukturální hrozba, kterou předchozí recenze přehlédly, protože všechny sdílely reprezentacionalistický předpoklad (kovariance není reprezentace; těžký problém obsahu).
- **Modální logika P-CMPLX a P-VAL:** dvojice „nutná a postačující podmínka“ cirkularitu přerozděluje, vyřešená tím není.
- **Petitio principii:** nosný „kvantitativní předpoklad“ předjímá odpověď na těžký problém.
- **„Sofistikovaná just-so story“:** platí zčásti, víc pro fenomenální vrstvu než pro kognitivní a afektivní vrstvy.
- **Kalibrace:** originalita spíš 10–15 %; zkreslení je architektonické, netýká se jen jednotlivých tvrzení.
- **Co doplnit:** formální teorii výpočetní složitosti pro prahy vědomí, hlenky (slime molds) jako kritický negativní test a Hoffmanovu teorii rozhraní jako vnitřní napětí s FEP.
- **Verdikt:** 5,5/10 jako model vědomí; 7–7,5/10 jako teorie kognice a regulace emocí, kdyby vypustil tvrzení o fenomenálním vědomí.

## K5. Konvergence s review „Opus“ (chat 11. 10. 2026)

- Path C působí spíš jako imunizace než jako skromnost.
- Nezávislost P-CMPLX a P-VAL neobstojí (protipříklad se SAT solverem).
- Zkreslení výběrem je architektonické: osm kol recenzí sdílelo jednu školu, takže jejich shoda není nezávislé potvrzení.
- Vrstva 0 může být nosná přes teleosemantiku (ukotvení obsahu) a nemusí být nejslabším článkem.

## K6. Přestavba na tři objekty (návrh Claude, chat 4. 7. 2026)

- **Theory A:** vtělená allostatická afektivní kognice.
- **Theory B:** teleodynamická sázka o valenci.
- **Lokalizovaná mezera:** přesně pojmenované místo, kde model nevysvětluje „holé“ vědomí.
- Součástí návrhu bylo vyřadit A/B hierarchii, ostrý práh PCI jako univerzální marker vědomí a Path C. Stav: čeká na [rozhodnutí](04-rozhodnuti.md).

## K7. P-MODE5 (chat 11. 7. 2026; z introspektivního pozorování)

- **Hypotéza:** hloubka a udržitelnost nedvojného stavu klesá s velikostí akutní tělesné potřeby (žízeň, hlad, bolest, plný močový měchýř), a to rychleji než při vnějším rozptýlení stejné intenzity. Fenomenologická kotva: Leder 1990, The Absent Body.
- **Test:** kontrolovaná hydratace a sytost × čas do kolapsu nedvojného reportu; otevřené zůstává, jak srovnat salienci podnětů.
- **Stupeň jistoty:** T3; hypotéza k testu, evidencí zatím není.
