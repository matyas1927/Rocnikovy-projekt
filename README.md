# Porovnání nositelných senzorových systémů ve sportu

## Úvod
Tento repozitář slouží jako kompletní dokumentace ročníkového projektu z předmětu **Mikropočítačové systémy**. Projekt je zpracováván průběžně během školního roku a veškeré materiály, dokumentace, schémata, zdrojové kódy a výsledky analýzy jsou ukládány právě zde.
Projekt se zaměřuje na využití mikropočítačových systémů v oblasti nositelné elektroniky. Konkrétně se zabývá porovnáním dvou nositelných senzorových zařízení – profesionálního sportovního trackeru **StatsSport** a chytrých hodinek **Apple Watch** – z hlediska přesnosti měření a zpracování pohybových dat.

## Cíl Projektu
Hlavním cílem projektu je porovnat přesnost a způsob zpracování dat dvou nositelných senzorových systémů používaných ve sportu – profesionálního trackeru StatsSport a chytrých hodinek Apple Watch.
Projekt se zaměřuje na analýzu vybraných měřených veličin, jako je vzdálenost, rychlost a pohybová aktivita, a na zhodnocení rozdílů v použitých senzorech a metodách zpracování dat.
Projekt je pojat z technického hlediska a soustředí se především na problematiku mikropočítačových systémů a senzorové techniky.

# Myšlenková mapa projektu
Tato kapitola obsahuje myšlenkovou mapu ročníkového projektu. Myšlenková mapa slouží k přehlednému rozdělení projektu na jednotlivé oblasti a pomáhá při jeho postupném zpracování.

## Myšlenková mapa
![Myšlenková mapa](images/myslenkova_mapa.png)


## Popis myšlenkové mapy
Středem myšlenkové mapy je téma porovnání nositelných senzorových systémů. Jednotlivé větve znázorňují hlavní oblasti projektu, jako jsou použitá zařízení, senzory a hardware, měření a sběr dat, zpracování dat a vyhodnocení výsledků.

Myšlenková mapa byla vytvořena v úvodní fázi projektu a bude sloužit jako podklad pro další rozpracování jednotlivých kapitol.

# Současný stav projektu
V této kapitole je popsán aktuální stav ročníkového projektu.

Projekt se v současné době nachází ve fázi rozpracování. Bylo stanoveno téma projektu, jeho cíl a základní struktura dokumentace. Dále byla vytvořena myšlenková mapa, která slouží jako přehled plánovaných částí projektu.

V rámci praktické části projektu již bylo zahájeno základní sbírání dat z nositelných zařízení. Tato činnost zatím slouží především k seznámení se s funkcemi zařízení, dostupnými daty a možnostmi jejich exportu a dalšího zpracování. Hlavní důraz je v této fázi kladen především na teoretickou část projektu.

Praktická část projektu bude dále rozvíjena v následujících etapách, kdy dojde k plánovanému a opakovanému měření za stejných podmínek a následnému vyhodnocení získaných dat.

# Použitá zařízení
V této kapitole jsou popsána zařízení, která jsou použita v rámci ročníkového projektu pro měření a sběr pohybových dat.

## STATSports Tracker
- STATSports Tracker je profesionální sportovní GPS zařízení určené především pro sledování výkonu hráčů v kolektivních sportech, jako je fotbal. Zařízení se běžně nosí v elastické vestě na zádech hráče mezi lopatkami.
- Tracker zaznamenává pohyb hráče během tréninku nebo zápasu a ukládá data, která jsou následně analyzována pomocí specializovaného softwaru.
- Tento tracker využívám i já sám, a to pro sledování vlastního výkonu a zlepšování fyzické kondice při tréninku.
![Tracker](images/Sportstracker.jpeg)


## Apple Watch
- Apple Watch jsou chytré hodinky určené pro běžné uživatele. Kromě sledování času umožňují také měření pohybové aktivity, sportovních výkonů a zdravotních údajů jako je třeba měření kvality spánku, srdečního tepu a další.
- Hodinky jsou vybaveny několika senzory, které umožňují sledovat pohyb, vzdálenost a další parametry při sportovní aktivitě. Díky tomu jsou vhodné i pro základní porovnání s profesionálním sportovním trackerem.
- Apple Watch využívám především ke sledování kvality spánku, počtu kroků a základních zdravotních údajů, což mi pomáhá lépe hlídat denní režim a celkový zdravotní stav.
![Applewatch](images/applewatch.jpeg)

## Shrnutí kapitoly

Krátké shrnutí, že se jedná o dvě rozdílná zařízení určená pro odlišné skupiny uživatelů, což je důležité pro další porovnání.

# Senzory a hardware

V této kapitole jsou popsány základní senzory a hardwarové prvky, které jsou využívány v zařízeních STATSports Tracker a Apple Watch pro měření pohybových dat.

Obě zařízení obsahují mikropočítačový systém, který zajišťuje sběr dat ze senzorů, jejich zpracování a následné uložení nebo přenos k další analýze.

## Akcelerometr

Akcelerometr je senzor, který slouží k měření zrychlení pohybu zařízení v jednotlivých osách. V nositelných zařízeních se nejčastěji používá tříosý akcelerometr, který umožňuje sledovat pohyb ve směrech os X, Y a Z.
Pomocí akcelerometru lze zaznamenat například změny rychlosti, kroky, nárazy nebo intenzitu pohybu. Tento senzor je klíčový pro vyhodnocování pohybové aktivity sportovce.

## Gyroskop

Gyroskop je senzor určený k měření úhlové rychlosti a orientace zařízení v prostoru. Umožňuje určit, jakým směrem a jak rychle se zařízení otáčí.
V kombinaci s akcelerometrem poskytuje gyroskop přesnější informace o pohybu, například o změnách směru běhu nebo o poloze těla během sportovní aktivity.

## GPS (Globální polohový systém)

GPS senzor slouží k určení polohy zařízení pomocí signálů z družic. Na základě získaných dat je možné vypočítat vzdálenost, rychlost pohybu a trasu, po které se uživatel pohyboval.
GPS je důležitým senzorem zejména u venkovních sportovních aktivit, jako je běh nebo fotbal, kde je nutné sledovat pohyb v prostoru.

## Další senzory

Apple Watch obsahují také další senzory, například snímač srdečního tepu, barometr nebo kompas. Tyto senzory umožňují rozšířené sledování sportovní aktivity a zdravotního stavu uživatele.
STATSports Tracker je naopak zaměřen především na přesné měření pohybu a polohy, a proto využívá hlavně pohybové senzory a GPS modul.

## Shrnutí kapitoly

V této kapitole byly popsány základní senzory a hardwarové prvky používané v nositelných zařízeních. Tyto senzory tvoří základ pro měření a zpracování pohybových dat, která budou dále analyzována v praktické části projektu.



























# Zdroje a citace
Níže jsou uvedeny zdroje informací, které byly použity při zpracování ročníkového projektu.

--

- STATSports. Online. STATSports | Performance Powered By Data | Athlete Monitoring. 2008. Dostupné z: https://statsports.com/. [cit. 2025-12-13].
- Apple. Online. Apple (Česká republika). 1994. Dostupné z: https://www.apple.com/cz/. [cit. 2025-12-13].
- GPS vesta na fotbal – jak funguje a vyplatí se? Online. 2022. Dostupné z: https://topkopacky.cz/gps-vesta-fotbal/. [cit. 2025-12-13].
- 31 Years of Apple.com Website Design History - 39 Images - Version Museum. Online. Version Museum. Dostupné z: https://www.versionmuseum.com/history-of/apple-website. [cit. 2025-12-13].
- Nadvláda Apple Watch končí! iOS 26.3 přinese zásadní změnu, díky které s nimi konkurence srovná krok. Letem Světem Applem. 2025, s. 1.
- Tenčí, odolnější a s delší výdrží. Test hodinek Apple Watch Series 11. IDNES.cz. 2025, roč. 2013, č. 2, s. 1.

