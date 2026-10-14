# Architektura modelu v3.x

[← Přehled v3](README.md)

> Stav: shrnutí v3.1 s vyznačenými opravami pro v3.2 (14. 10. 2026). Plná znění jednotlivých vrstev v3.1 zatím zůstávají v pracovní verzi autora; tady je u každé části její tvrzení, deklarovaný a navržený stupeň jistoty, verdikt revize a co je potřeba upravit.

## Abstrakt v3.0

Vědomí vzniká v mozku, ale je konstitutivně závislé na těle a existuje ve službách replikace, ne přežití jako takového. Model má 9 vrstev (L0–L8) a 3 principy napříč vrstvami (P-CMPLX, P-VAL, P-REPL).

## Co přinesla v3.0 oproti v2.6

- Nahoře: vtělené prediktivní zpracování pod replikačním imperativem s allostatickým rozpočtem (v2.6: pod allostatickým omezením).
- Nové vrstvy: L0 Replikační imperativ a L8 PCI a empirická operacionalizace.
- L3 doplněna o předpojmový afektivní substrát (PAG, parabrachiální oblast); L4 o mechanismus přechodů přes váhování precision (REBUS); L5 o anatomii po studii Cogitate.
- Tři explicitní principy napříč vrstvami: P-CMPLX, P-VAL, P-REPL.
- A/B hierarchie obhájená klinickými daty; postoj k těžkému problému „částečně řešen přes P-VAL“ (revize v3.2 navrhuje tuto formulaci stáhnout, viz [rozhodnutí](04-rozhodnuti.md)).

## Stupně jistoty

- **T1:** silná empirická podpora, recenzovaný konsenzus 2023–2026.
- **T2:** věrohodný mechanismus, směrová evidence bez konsenzu.
- **T3:** spekulace, dosud netestované.

## Vrstvy a principy

### L0 Replikační imperativ

- **Stav po revizi:** Zásadní problém
- **Stupeň jistoty:** deklarováno T2, navrženo mimo vrstvy

**Co tvrdí.** Organismy jsou evolucí nastavené hlavně na předání genů; přežití jedince je jen prostředek. Vědomí je podle této vrstvy nástroj, který replikaci slouží. Ilustrace: losos po vytření umírá, protože jeho tělo „splnilo úkol“.

**Verdikt revize.** Myšlenka sama patří ke standardní evoluční biologii. Problém je v tom, kam ji model staví: do jedné řady s mechanismy mozku, kde hledá číselný rozdíl oproti principu volné energie. Obě teorie odpovídají na jinou otázku, takže takový rozdíl najít nejde.

**Co upravit.** Podle rozhodnutí zrušit jako vrstvu a obsah přesunout do sekce „Evoluční omezení“. Opravit údaje o chobotnici a o pavoucích.

**Rozpory:** [Vrstva 0 míchá dvě úrovně vysvětlení](03-rozpory.md#l0)

### L1 Prediktivní zpracování

- **Stav po revizi:** K opravě
- **Stupeň jistoty:** deklarováno T1, navrženo T2 jako mechanismus v neuronech

**Co tvrdí.** Mozek neustále odhaduje, co mu smysly za okamžik pošlou, a zpracovává hlavně rozdíl mezi odhadem a skutečností, tedy predikční chybu. Proto zakopneš o schod, který má jinou výšku, než mozek čekal.

**Verdikt revize.** Jako rámec drží a v oboru je dominantní. Citace, o kterou vrstva opírá nejvyšší stupeň jistoty, je ale chybná: skutečná studie je z roku 2021 a ukazuje smíšenější obrázek. Tvrzení „takhle to v neuronech opravdu funguje“ proto patří na T2.

**Co upravit.** Ficco 2021 místo „Ficco 2024“; prediktivní zpracování jako mechanismus na T2; přesunout P1, P5 a P7 do vrstev, ze kterých plynou; P7 na T2; smazat „90 % predikce“; přidat P-ANAT3 (INTREPID).

**Rozpory:** [Vrstva 0 míchá dvě úrovně vysvětlení](03-rozpory.md#l0)

**Opravy faktů:** [Hlavní opora vrstvy 1 je jiná studie](02-errata.md#ficco); [Lucidní snění: hlavní EEG doklad jsou artefakty](02-errata.md#p7); [Čekané milníky: INTREPID a Cogitate 2](02-errata.md#miles)

### L2 Allostatický engine

- **Stav po revizi:** K opravě
- **Stupeň jistoty:** deklarováno T1, navrženo T1 mechanismus, T2 role ve vědomí

**Co tvrdí.** Mozek řídí tělo s předstihem: chystá energii, cukr a hormony dřív, než budou potřeba. Tomu se říká allostáza. Podle modelu je to „energetická páteř“, ze které vychází emoce, motivace i únava.

**Verdikt revize.** Allostáza je dobře doložená. Vrstva ale nemá jedinou vlastní testovatelnou predikci, přestože nese nejvyšší stupeň jistoty. Popis deprese jako „nedostatečné anticipace“ odporuje výzkumu, ze kterého vrstva vychází: podle Barrettové a kolegů mozek v depresi náklady na energii nadhodnocuje a drží se strnulých předpovědí.

**Co upravit.** Přepsat popis deprese; doplnit vlastní predikce; ADHD nahradit odkazem na vrstvu 6.

**Rozpory:** [ADHD má v modelu čtyři různé mechanismy](03-rozpory.md#adhd)

### L3 Emoce jako výklad tělesných signálů

- **Stav po revizi:** K opravě
- **Stupeň jistoty:** deklarováno T1, navrženo T2 (hybrid)

**Co tvrdí.** Emoce jako vztek nebo radost jsou podle modelu výklad, který mozek přidá k tělesným signálům. Pod tím běží staré podkorové okruhy, například PAG v mozkovém kmeni. Amygdala je od května popsaná spíš jako detektor toho, na čem záleží.

**Verdikt revize.** Vrstva spojuje dvě soupeřící teorie emocí a neříká, jak jdou dohromady. Amygdalu označuje za nezbytnou pro citový život, což klinické případy nepodporují. Část citací z květnové rešerše se nedaří dohledat.

**Co upravit.** Hybrid Barrettové a Pankseppa; vyřadit amygdalu ze seznamu nezbytných struktur; ověřit citace v bodech 0d a 1j.

**Rozpory:** [Emoce: dvě soupeřící teorie v jedné vrstvě](03-rozpory.md#l3)

### L4 Tři módy vědomí

- **Stav po revizi:** Zásadní problém
- **Stupeň jistoty:** deklarováno T2, navrženo T2 (mapa stavů)

**Co tvrdí.** Vědomí má podle modelu tři režimy: ukotvený v těle (běžná bdělost), ponořený do myšlení a nedvojný (pokročilá meditace). Mezi nimi přepíná nastavení vah, tedy jak moc mozek věří svým očekáváním. Psychedelika popisuje příbuzný model REBUS.

**Verdikt revize.** Mód 2 i mód 3 slučují stavy, které se v mozku chovají opačně, a příklad se Stephenem Hawkingem dokládá něco jiného, než vrstva tvrdí. Návrh: nahradit tři módy mapou s několika osami.

**Co upravit.** Rozdělit Mód 3; Mód 2 rozdělit, nebo přejít na mapu stavů; Hawkinga nahradit afázií; ověřit citace v bodu 1g; REBUS na T2; sjednotit ketamin s vrstvou 6.

**Rozpory:** [Mód 3 slučuje tři různé stavy](03-rozpory.md#mode3); [Mód 2 obsahuje dva opačné stavy](03-rozpory.md#mode2); [Dopamin: vrstva popírá, na čem staví](03-rozpory.md#l6)

**Opravy faktů:** [Cessation: co zatím víme z dat](02-errata.md#cess)

### L5 Distribuovaná architektura

- **Stav po revizi:** K opravě
- **Stupeň jistoty:** deklarováno T1, navrženo T1–T2

**Co tvrdí.** Obsah toho, co právě prožíváš, tedy co vidíš a slyšíš, vzniká hlavně v zadní části mozkové kůry. Přední část (prefrontální kůra) vybírá, hodnotí a umožňuje o prožitku podat zprávu. Model to opírá o studii Cogitate.

**Verdikt revize.** Jádro odpovídá datům. Stránka si ale protiřečí v roce vydání studie Cogitate, výsledky podává ostřeji, než je studie ukázala, a zařazuje sem věci, které patří jinam (Libet, INTREPID).

**Co upravit.** Doplnit výsledky Cogitate 2025; opravit datum kritiky IIT; P-ANAT3 přesunout do vrstvy 1; Libeta přesunout k tématu jednání.

**Rozpory:** [Mód 2 obsahuje dva opačné stavy](03-rozpory.md#mode2)

**Opravy faktů:** [Studie Cogitate: rok vydání a výsledky](02-errata.md#cogitate); [Kritika IIT jako pseudovědy: kdy a kde vyšla](02-errata.md#iit); [Čekané milníky: INTREPID a Cogitate 2](02-errata.md#miles)

### L6 Dopamin jako alokátor rozpočtu

- **Stav po revizi:** K opravě
- **Stupeň jistoty:** deklarováno T2, navrženo T1 fázický, T2 tonický

**Co tvrdí.** Dopamin podle modelu funguje jako manažer rozpočtu: rozhoduje, kolik energie do čeho vložit. ADHD je v tomto pohledu porucha alokace a stimulancia pomáhají mozku „věřit“ vlastnímu motivačnímu signálu.

**Verdikt revize.** Myšlenka rozpočtového manažera má oporu ve výzkumu pomalé (tonické) složky dopaminu. Vrstva ale popírá, že dopamin nese predikční chybu odměny, a o pár odstavců dál na ní staví. Tvrzení, že stimulancia nezvyšují hladinu dopaminu, je fakticky chybné.

**Co upravit.** Opravit tvrzení o stimulanciích; sjednotit roli predikční chyby; sjednotit ketamin s vrstvou 4; jedna definice ADHD; stáhnout „confirmed“ u P6.

**Rozpory:** [Dopamin: vrstva popírá, na čem staví](03-rozpory.md#l6); [ADHD má v modelu čtyři různé mechanismy](03-rozpory.md#adhd)

**Opravy faktů:** [Metaanalýza „Cortese 2024 Lancet“ se nedá dohledat](02-errata.md#p6)

### L7 Allostatická zátěž

- **Stav po revizi:** K opravě
- **Stupeň jistoty:** deklarováno T2 (spánek T1), navrženo T2

**Co tvrdí.** Když tělo dlouho reguluje pod tlakem, rozpočet se vyčerpá jako přečerpaná kreditní karta; výsledkem může být vyhoření nebo deprese. V květnu sem přibyl spánek jako noční údržba systému.

**Verdikt revize.** Rámec allostatické zátěže je užitečný. Čištění mozku ve spánku je ale od roku 2024 sporné a ADHD je zařazené mezi důsledky vyčerpání, ačkoli jde o vývojovou poruchu. U jedné predikce stránka uvádí, že neexistuje publikovaný test, přitom blízká studie existuje.

**Co upravit.** Glymfatika na T2; obrátit kauzalitu u ADHD; doplnit studii k P-SLEEP1; přejmenovat „P7-style“; ověřit citaci o REM spánku.

**Rozpory:** [ADHD má v modelu čtyři různé mechanismy](03-rozpory.md#adhd)

**Opravy faktů:** [Čištění mozku ve spánku je sporné](02-errata.md#glymph)

### L8 PCI a měření vědomí

- **Stav po revizi:** K opravě
- **Stupeň jistoty:** deklarováno T1, navrženo T1 (kapacita, dospělí)

**Co tvrdí.** PCI je klinický test schopnosti vědomí: magnetický impulz ťukne do mozkové kůry a EEG měří, jak složitě mozek odpoví. Bohatá odpověď znamená, že mozek je schopen vědomí; pod hodnotou kolem 0,31 jde o stavy bez vědomí, jako je hluboký spánek nebo narkóza.

**Verdikt revize.** PCI jako měřítko kapacity drží a patří k nejlépe ověřeným částem modelu. Tabulka hodnot pro jednotlivé stavy ale obsahuje vyvrácený řádek (psychedelika), řádek v rozporu s vlastním rozhodnutím (cessation) a čísla bez zdroje.

**Co upravit.** Opravit řádky psychedelika, cessation, vegetativní stav, locked-in a mozková smrt; přeformulovat P-PCI3; čísla bez zdroje označit jako orientační.

**Rozpory:** [Mód 3 slučuje tři různé stavy](03-rozpory.md#mode3); [A/B hierarchie si protiřečí](03-rozpory.md#ab); [P-CMPLX: tři pojmy pod jedním slovem](03-rozpory.md#cmplx)

**Opravy faktů:** [PCI pod psychedeliky neroste](02-errata.md#pcipsy); [Skryté vědomí u čtvrtiny nereagujících pacientů](02-errata.md#cmd); [Cessation: co zatím víme z dat](02-errata.md#cess)

### P-CMPLX Arbitrace nesnížitelného konfliktu

- **Stav po revizi:** Zásadní problém
- **Stupeň jistoty:** deklarováno T2, navrženo T2 (syntéza)

**Co tvrdí.** Vědomí podle tohoto principu vzniká tam, kde systém musí rozsoudit mnoho neslučitelných signálů, které soupeří o jedno tělo. Dav, který jde jedním směrem, rozhodčího nepotřebuje; dav, který se tlačí do jedné uličky ze dvou stran, ano.

**Verdikt revize.** Pod slovem „nesnížitelný“ se skrývají tři různé věci, které se měří odlišně. Myšlenka má výrazné předchůdce, takže jde o syntézu. Dvě predikce jsou postavené tak, že je nejde provést.

**Co upravit.** Rozlišit tři pojmy; vymezit se vůči Morsellovi; přeformulovat P-CMPLX1 a P-PCI3; P-CMPLX3 přesunout do P-VAL; opravit atribuci Merkerovi.

**Rozpory:** [Mód 3 slučuje tři různé stavy](03-rozpory.md#mode3); [A/B hierarchie si protiřečí](03-rozpory.md#ab); [P-CMPLX: tři pojmy pod jedním slovem](03-rozpory.md#cmplx)

**Opravy faktů:** [Cessation: co zatím víme z dat](02-errata.md#cess)

### P-VAL Prožitek jako tvar rozhodování

- **Stav po revizi:** Čeká na rozhodnutí
- **Stupeň jistoty:** deklarováno T3, navrženo T3

**Co tvrdí.** Prožívání je podle tohoto principu „tvar“ rozhodování v systému, kterému na výsledku záleží. Bez struktury „chci, nechci“ by nebylo nic, co by se prožívalo.

**Verdikt revize.** V různých místech existují tři verze postoje k těžkému problému. Jakmile autor vybere jednu, je potřeba s ní srovnat texty a predikce. Dvě predikce narážejí na klinická data.

**Co upravit.** Zapsat zvolenou verzi; opravit P-VAL1 (amygdala, mozkový kmen); vyřešit střet P-VAL2 s P-CMPLX; P-VAL3 zpřesnit přes prekérnost.

**Rozpory:** [P-CMPLX: tři pojmy pod jedním slovem](03-rozpory.md#cmplx); [Emoce: dvě soupeřící teorie v jedné vrstvě](03-rozpory.md#l3)

### P-REPL Vědomí vázané na replikaci

- **Stav po revizi:** Zásadní problém
- **Stupeň jistoty:** deklarováno T2–T3, navrženo mimo vrstvy

**Co tvrdí.** Vědomí by podle tohoto principu mělo být hlavně u druhů, které mají málo potomků, dlouho o ně pečují a žijí ve složitých skupinách. Eusociální hmyz by měl mít individuálního vědomí méně než hmyz samotářský.

**Verdikt revize.** Chobotnice je protipříklad, rámec r/K je v ekologii překonaný a model sám cituje deklaraci vědců, která připouští vědomí mnohem šířeji. Princip stojí a padá s vrstvou 0.

**Co upravit.** Nahradit r/K teorií životní strategie; přiznat chobotnici jako protipříklad; srovnat s NY Declaration; rozložení vědomí mezi druhy řešit přes UAL a dimenze vědomí.

**Rozpory:** [Vrstva 0 míchá dvě úrovně vysvětlení](03-rozpory.md#l0); [P-CMPLX: tři pojmy pod jedním slovem](03-rozpory.md#cmplx)

## Sebereflexe v3.0 (s poznámkami revize)

- **Mainstream ~60 %:** prediktivní zpracování, allostáza a interocepce, PCI, posteriorní anatomie obsahu (Cogitate), REBUS, subkortikální afektivní základy, paměť jako rekonstrukce, NY Declaration on Animal Consciousness 2024. Revize: dvě opory jsou chybně citované (Ficco 2024, Cortese 2024 Lancet), viz [errata](02-errata.md).
- **Originální syntéza ~30 %:** replikační imperativ proti nefalzifikovatelnosti FEP, A/B hierarchie, jednotný hierarchický emoční engine, dopamin jako alokátor rozpočtu, Mode 3 proti REBUS, tři principy v jednom modelu. Revize: P-CMPLX má výrazné předchůdce (Morsella, Merker, Cisek); adversariální review z 11. 10. 2026 odhaduje originalitu na 10–15 %.
- **Riziko zkreslení ~10 %:** jedna myšlenková škola (Barrett, Seth, Friston), výběr linie Solms/Damasio/Panksepp podle intuice, REBUS jako elegantní sjednocení, styl rozpoznávání vzorců. Revize: „riziko zkreslení“ je odhad pravděpodobnosti, nesčítá se s podíly obsahu; všech osm kol recenzí sdílelo reprezentacionalistický předpoklad.
