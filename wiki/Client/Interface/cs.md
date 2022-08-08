# Rozhraní

Tento článek vysvětluje vše, co potřebujete vědět o používání herního klienta osu!. Najdete zde informace ohledně obrazovky výběru skladby, ukazatele žebříčků a obrazovky výsledného skóre. Po spuštění herního klienta se zobrazí následující obrazovka:

![](img/intro-screen.jpg "Úvodní obrazovka")

## Hlavní menu

![](img/main-menu.jpg "Hlavní menu")

- \[1\] [osu! sušenka](/wiki/Client/Interface/Cookie). Po kliknutí na ní se zobrazí hlavní menu. Pulsuje podle [BPM](/wiki/Beatmapping/Beats_per_minute) hudby a kolem se roztahují sloupce, které vizualizují zvukové spektrum. Pokud se nepřehrává žádná skladba, pulzuje pomalým tempem 60 BPM.
- \[2\] Kliknutím na `Play` (nebo stisknutím `P`) si můžete zahrát hru osu! sami nebo s ostatními.
- \[3\] Kliknutím na `Edit` (nebo stisknutím `E`) upravíte [beatmapu](/wiki/Beatmap).
- \[4\] Kliknutím na `Options` (nebo stisknutím `O`) otevřete postranní panel [nastavení](/wiki/Client/Options).
- \[5\] Kliknutím na `Exit` (nebo stisknutím `Esc`) ukončíte hru.
- \[6\] Náhodný užitečný tip.
- \[7\] [ppy](https://ppy.sh/) logo s autorskými informacemi. Odkazuje na [osu! webovou stránku](https://osu.ppy.sh/home).
- \[8\] Pokud se vyskytnou problémy s připojením na [Bancho server](/wiki/Bancho_(server)) zobrazí se zde ikona rozbitého řetězu.
- \[9\] [Herní chat](/wiki/Client/Interface/Chat_console) a vlevo od něj tlačítko pro jeho rozšíření, které zobrazuje seznam aktuálně online uživatelů. Dá se také vyvolat pomocí `F8` a `F9`.
- \[10\] Hra obsahuje svůj vlastní přehrávač hudby, který náhodně přehrává skladby z vaší knihovny. Legenda níže.
- \[11\] Počet dostupných [obtížností beatmap](/wiki/Beatmap/Difficulty), doba, po kterou hrajete, a váš systémový čas.
- \[12\] Váš profil. Kliknutím na něj se zobrazí [možnosti uživatele](#user-options).

---

Herní přehrávač má následující tlačítka:

| Tlačítko | Popis |
| :-: | :-- |
| ![](img/jukebox/previous-track.jpg "Previous track") | Předchozí skladba |
| ![](img/jukebox/play.jpg "Play") | Play |
| ![](img/jukebox/pause.jpg "Pause") | Pause |
| ![](img/jukebox/stop.jpg "Stop the music!") | Zastavení přehrávání a posunutí skladby na začátek |
| ![](img/jukebox/next-track.jpg "Next track") | Následující skladba |
| ![](img/jukebox/view-song-info.jpg "View song info") | Přepínač mezi trvalým zobrazením informací o hrající skladbě a jejich zhasnutím po určité době. |
| ![](img/jukebox/jump-to-window.jpg "Jump To window") | Přeskočení na konkrétní skladbu. Skladby můžete vyhledávat nebo filtrovat podle Kolekcí. |

Herní přehrávač lze ovládat také pomocí [klávesových zkratek](/wiki/Client/Keyboard_shortcuts#jukebox).

## Možnosti uživatele

![](img/user-options.jpg "User options")

Na tuto obrazovku se dostanete kliknutím na svůj profil v levé horní části hlavní nabídky. Kteroukoli položku můžete vybrat stisknutím jejího příslušného čísla:

- `1. Zobrazit profil`: Zobrazí váš profil na webových stránkách.
- `2. Odhlásit se`: Odhlášení z vašeho účtu. Po odhlášení vás hra vyzve k opětovnému přihlášení.
- `3. Změnit profilový obrázek`: Otevře [stránku na úpravu avataru](https://osu.ppy.sh/home/account/edit#avatar).
- `4. Zavřít`: Zavře toto dialogové okno.

## Play menu

![](img/play-menu.jpg "Play menu")

Po vybrání `Play` v hlavním menu, dostanete tři možnosti:

- Klikněte `Solo` (nebo stiskněte `P`) pro samostatné hraní. Tato možnost vede na [obrazovku výběru skladby](#song-select).
- Klikněte `Multi` (nebo stiskněte `M`) pro hraní s více hráči. Tato možnost vede do [seznamu místností pro více hráčů](/wiki/Client/Interface/Multiplayer).
- Klikněte `Back` pro návrat do hlavního menu.

## Místnost pro více hráčů

*Hlavní stránka: [Multi](/wiki/Client/Interface/Multiplayer)*

![](img/multi-lobby.jpg "Multiplayer lobby")

Místnost pro více hráčů, anglicky "Multiplayer lobby", umožňuje hrát s nebo proti ostatním hráčům.

## Výběr skladeb

![](img/song-selection.jpg "Song select")

Anglicky "Song select".
Ikona momentálně vybraného [herního módu](/wiki/Game_mode) jde vidět v možnostech dole vlevo, nad tlačítkem `Mode`. Ikona módu lze také matně vidět uprostřed obrazovky. V osu! jsou čtyři herní módy:

- ![](/wiki/shared/mode/osu.png) [osu!](/wiki/Game_mode/osu!)
- ![](/wiki/shared/mode/taiko.png) [osu!taiko](/wiki/Game_mode/osu!taiko)
- ![](/wiki/shared/mode/catch.png) [osu!catch](/wiki/Game_mode/osu!catch)
- ![](/wiki/shared/mode/mania.png) [osu!mania](/wiki/Game_mode/osu!mania)

Než budete pokračovat, tato obrazovka obsahuje příliš mnoho prvků, než aby bylo možné je poznamenat pomocí snadno viditelných čísel. V následujících podkapitolách se zaměříme vždy na jednu část obrazovky, a to shora dolů a zleva doprava.

### Informace beatmapy

![](img/metadata-comparison.jpg)

Tato část zobrazuje **informace o vybrané obtížnosti.** Po vstupu do výběru skladeb se automaticky zvolí skladba, která hrála v hlavním menu. Ikona vlevo nahoře reprezentuje [kategorii beatmapy](/wiki/Beatmap/Category), která je v tomto případě [hodnocená](/wiki/Beatmap/Category#ranked).

Název skladby se obvykle zobrazuje romanizovaně (dolní obrázek), ale pokud zapnete v [Nastavení](/wiki/Client/Options) možnost `Preferovat metadata v originálním jazyce`, název se ukáže v unikódu (horní obrázek). Název obtížnosti je mezi hranatými závorkami (`[]`). Tvůrce mapy je pod názvem mapy, níže najdeme další informace. Zleva doprava, hodnoty jsou:

- **Délka**: Celková délka mapy od začátku do konce včetně přestávek. Nezaměňovat s [drain time](/wiki/Gameplay/Drain_time).
- **BPM**: *Úhozy za minutu*, tempo skladby. Pokud jsou zde uvedeny dvě hodnoty, a jedna v závorce, znamená to, že se BPM v průběhu skladby mění. Zobrazuje nejpomalejší a nejrychlejší BPM. Hodnota v závorce je nejčastější BPM v beatmapě.
- **Objekty**: Celkový počet [objektů](/wiki/Hit_object) v beatmapě.
- **Kruhy**: Celkový počet [kruhů](/wiki/Hit_object/Hit_circle) (osu! a osu!taiko), [fruits](/wiki/Hit_object/Fruit) (osu!catch), nebo normálních not v (osu!manii) v beatmapě.
- **Slidery**: Celkový počet [sliderů](/wiki/Hit_object/Slider) (osu!), drumrolls (osu!taiko), [fruit streams](/wiki/Hit_object/Juice_stream) (osu!catch), nebo hold not (osu!mania) v beatmapě.
- **Spinnery**: Celkový počet [spinnerů](/wiki/Hit_object/Spinner) (osu!), dendens (osu!taiko), nebo [banana showers](/wiki/Hit_object/Banana) (osu!catch) v beatmapě.
- **OD**: [Overall difficulty](/wiki/Beatmapping/Overall_difficulty) beatmapy.
- **HP**: [HP drain rate](/wiki/Beatmapping/HP_drain_rate). Více o [health](/wiki/Gameplay/Health).
- **Stars**: [Star rating](/wiki/Beatmapping/Star_rating) beatmapy. Počet hvězd je také snadno viditelný na záložce beatmapy.

### Seskupování a seřazování

![](img/beatmap-filters.jpg)

Kliknutím na jednu ze záložek **seřadíte nebo seskupíte seznam skladeb podle vybraného kritéria**.

#### Seskupení

Tyto možnosti seskupí beatmapy do různých skupin:

| Seskupení | Popis |
| :-: | :-- |
| `Žádné seskupení` | Beatmapy nebudou seskupeny, ale budou stále seřazeny podle Seřazení |
| `Podle Obtížnosti` | Beatmapy budou seskupeny podle jejich Star ratingu. |
| `Podle Umělce` | Beatmapy budou seskupeny podle prvního písmena názvu umělce skladby. |
| `Nedávno Hrané` | Beatmapy budou seskupeny podle toho kdy jste je naposledy hráli. |
| `Kolekce` | Zobrazí kolekce které jste vytvořili. *Pozor! Toto skryje veškeré mapy které nejsou v kolekci/ích.* |
| `Podle BPM` | Beatmapy budou seskupeny do skupin po 60 BPM. |
| `Podle Autora` | Beatmapy budou abecedně seskupeny podle prvního písmena názvu autora. |
| `Podle Data Přidání` | Beatmapy budou seskupeny podle data přidání, od dneška až po 5 a více měsíců zpět |
| `Podle Délky` | Beatmapy budou seskupeny podle délky: 1 minut(a) nebo méně, 2 minut(a) nebo méně, 3, 4, 5, 10, a přes 10 minut. |
| `Podle Módu` | Beatmapy budou seřazeny podle jejich herního módu. |
| `Podle Dosáhnutého Ranku` | Beatmapy budou seskupeny podle nejlepšího dosaženého [ranku](/wiki/Gameplay/Grade). |
| `Podle Názvu` | Beatmapy budou abecedně seskupeny podle prvního písmena jejich názvu. |
| `Oblíbené` | Zobrazí pouze mapy které jste si online oblíbili. |
| `Moje Mapy` | Zobrazí pouze mapy které jste namapovali (tj. ty u kterých se jméno autora shoduje s vaším jménem ve hře). |
| `Status Hodnocení` | Beatmapy budou seskupeny podle jejich statusu: hodnocené, kvalifikované, nevyřízené, nepředložené, nebo loved.  |

Prvních 5 je vyvolatelných pomocí záložek pod Skupina a Seřadit.

#### Seřazování

Seřadí mapy v určitém řádu.

| Kritérium řazení | Popis |
| :-: | :-- |
| `Podle Umělce` | Beatmapy budou abecedně seřazeny podle názvu umělce. |
| `Podle BPM` | Beatmapy budou seřazeny od nejvyššího po nejnižší, pokud má mapa více BPM bere se to nejvyšší. |
| `Podle Autora` | Beatmapy budou abecedně seřazeny podle jejich autora. |
| `Podle Data Přidání` | Beatmapy budou seřazeny podle toho kdy byly přidány, od nejstarší po nejnovější. |
| `Podle Obtížnosti` | Beatmapy budou seřazeny podle jejich Star ratingu, od nejjednodušší po nejtěžší. *Pozor! Toto rozdělí obtížnosti beatmap.* |
| `Podle Délky` | Beatmapy budou seřazeny podle jejich délky, od nejkratší po nejdelší. |
| `Podle Dosáhnutého Ranku` | Beatmapy budou seřazeny podle na nich dosaženém ranku, od nejhoršího po nejlepší. |
| `Podle Názvu` | Beatmapy budou abecedně seřazeny podle jejich názvu. |

### Hledání

![](img/search-bar.jpg)

*Poznámka: Při hledání nemůžete mít otevřený chat nebo postranní panel nastavení, pokud tomu tak bude všechno co napíšete bude vnímáno jako chatový text nebo hledání v postranním panelu nastavení. *

Po vyhledání se zobrazí pouze beatmapy splňující vámi zadaná kritéria. Ve výchozím stavu bude každé hledání srovnáváno s umělci, názvy, autory, a tagy beatmapy.

Kromě hledání jste taky schopni používat filtry, pomocí kterých můžete hledat v dalších metadatech, a to spojením jednoho z podporovaných filtrů se srovnávacím znaménkem a hodnotou(např. `ar=9`).

Podporované filtry:

| Filtr | Popis |
| :-: | :-- |
| `artist` | Název umělce |
| `creator` | Název autora |
| `title` | Název skladby |
| `difficulty` | Název obtížnosti |
| `ar` | [Approach Rate](/wiki/Beatmapping/Approach_rate) |
| `cs` | [Circle Size](/wiki/Beatmapping/Circle_size) |
| `od` | [Overall Difficulty](/wiki/Beatmapping/Overall_difficulty) |
| `hp` | [HP drain rate](/wiki/Beatmapping/HP_drain_rate) |
| `key`, `keys` | Počet kláves (pouze beatmapy osu!mania nebo jejich konverty) |
| `star`, `stars` | [Star rating](/wiki/Beatmapping/Star_rating) |
| `bpm` | BPM, *úhozy za minutu* |
| `length` | Délka v sekundách |
| `drain` | [Drain time](/wiki/Gameplay/Drain_time) v sekundách |
| `mode` | Herní mód. Může být `osu`, `taiko`, `catch`, nebo `mania`, nebo `o`/`t`/`c`/`m` ve zkratkách. |
| `status` | Status beatmapy. Může být `ranked`, `approved`, `pending`, `notsubmitted`, `unknown`, nebo `loved`, nebo `r`/`a`/`p`/`n`/`u`/`l` ve zkratkách. |
| `played` | Čas uběhlý od posledního zahrání ve dnech. |
| `unplayed` | Zobrazí pouze nehrané mapy. Musí se použít porovnání bez hodnoty (např. `unplayed=`). Porovnání je ignorováno. |
| `speed` | Uložená rychlost beatmapy v osu.manii. Pro nehrané mapy vždy 0 nebo pokud je možnost [`Pamatovat si na osu!manii rychlost dráhy`](/wiki/Client/Options#gameplay) vypnutá. |

Podporovaná srovnání:

| Srovnání | Popis |
| :-: | :-- |
| `=` nebo `==` | Je rovno |
| `!=` | Není rovno |
| `<` | Méně než |
| `>` | Více než |
| `<=` | Méně nebo rovno |
| `>=` | Více nebo rovno |

Můžete také vyhledat ID číslo obtížnosti a dostat jeden výsledek, tedy pokud hledanou mapu máte.

### Žebříčky

![](img/leaderboards.jpg)

 V žebříčcích se mohou nacházet:

- Oznámení `Not Submitted` oznamuje že beatmapa nebyla nahrána na osu! webovou stránku pomocí [Beatmap Submission System](/wiki/Submission) nebo byla vymazána autorem.
- Oznámení `Update to latest version` se ukáže pokud je pro beatmapu dostupná nová verze. Kliknutím stáhnete aktualizaci.
  - *Upozornění: Po aktualizaci mapy se vymažou veškerá lokální skóre na mapě. Záznamy se dají uložit pravým kliknutím na skóre.*
- Oznámení `Latest pending version` znamená že mapa sice je nahraná na osu! webovou stránku, ale není hodnocená.
- Pokud existují replaye, respektive skóre, odpovídající nastavení žebříčkům, budou zobrazeny namísto ostatních oznámení. Toto je možno vidět na obrázku výše.
  - Pod veřejnými žebříčky (např. Globální, Státní, etc.), je zobrazeno vaše nejlepší skóre i s vašim umístěním na žebříčku beatmapy.
- Oznámení `No records set!` znamená že pro aktuální nastavení žebříčku nejsou žádné dostupné záznamy (nejčastěji se objevuje v lokálním žebříčku pokud byla beatmapa právě stáhnuta nebo změněna).

Zde jsou všechna nastavení žebříčku:

- Lokální
- Státní\*
- Globální
- Globální (podle zvoleného módu)\*
- Přátelé\*

\*Vyžaduje [osu!supporter](/wiki/osu!supporter).

Kliknutím na ikonu textových bublin se vyvolá  **rychlý webový přístup k této beatmapě**:

- Stiskněte `1` nebo klikněte na `Beatmap Listing/Scores` pro otevření stránky beatmapy ve vašem webovém prohlížeči.
- Stiskněte `2` nebo klikněte na `Beatmap Modding` pro otevření [modding](/wiki/Modding) stránky beatmapy.
- Stiskněte `3`, `Esc` nebo klikněte na `Cancel` a vraťte se do výběru skladeb.

### Beatmap menu

![](img/beatmap-cards.jpg)

Beatmapové menu zobrazuje všechny dostupné beatmapy. Odlišné beatmapy mohou mít jiné barvy:

| Barva boxu | Popis |
| :-: | :-- |
| **Růžová** | Tato beatmapa nebyla dosud hrána. |
| **Oranžová** | Alespoň jedna obtížnost beatmapy byla dokončena. |
| **Světle modrá** | Beatmapa má více než jednu obtížnost. |
| **Bílá** | Aktuálně vybraná obtížnost. |

*Poznámka. Některé [skiny](/wiki/Skin) mohou barvy změnit*

Seznam beatmap můžete posunovat kolečkem u myši, kurzorovými klávesami, tažením a podržením levého tlačítka myši nebo držením pravého tlačítka myši (známé jako absolutní scrollování), které posune seznam na Y pozici myši. Kliknutím na mapu vyberete mapu, opětovným kliknutím, stiskem `Enter` nebo kliknutím na osu! cookie v pravém dolním rohu spustíte mapu.

### Herní nástroje

![](img/game-mode-selector.jpg "Seznam dostupných herních módů")

![](img/gameplay-toolbox.jpg)

Tuto část můžeme nazývat Sadou Herních Nástrojů. Budeme se věnovat jednotlivým tlačítkům zleva doprava.

Stiskněte `Esc` nebo klikněte tlačítko `Back` pro vrácení do hlavního menu.

Klikněte na tlačítko `Mode` a otevře se vám seznam herních módů v osu!. Alternativně můžete stisknout `Ctrl` společně s `1` (osu!), `2` (osu!taiko), `3` (osu!catch), nebo `4` (osu!mania) a změnit tím herní mód. Přepnutím do jiného herního módu se přepnou i [žebříčky](/wiki/Ranking), což lze také vidět na změně vašeho globálního ranku.

![](img/game-modifiers.jpg "Okno výběru modifikací")

Klikněte na tlačítko `Mods` nebo stiskněte `F1` pro otevření **[okna výběru modifikací](/wiki/Game_modifier)**.

V tomto okně můžete aplikovat modifikace (zkráceně "módy"). Některé módy sníží obtížnost, a nastaví násobič, který sníží dosažitelné skóre. Naopak zde máme módy které obtížnost zvýší, ale nastaví násobič, který zvýší dosažitelné skóre. Nakonec zde jsou módy které mění hru jiným způsobem. Do této kategorie patří [Relax](/wiki/Game_modifier/Relax) a [Auto Pilot](/wiki/Game_modifier/Autopilot).

Ukázáním myší na ikonu módu dostanete krátký popis jeho efektu. Kliknutím na ikonu módu se mód vybere nebo odebere. Některé módy, například Double Time, mají několik verzí — po opětovném kliknutí se mód změní na svoji druhou verzi. Hodnota Násobiče Skóre, ve hře "Score Multiplier", vyjadřuje kombinovaný efekt vámi vybranými módy na dosažitelném skóre. Kliknutím na `Vypnout všechny módy` nebo stisknutím `1` odeberete veškeré vybrané módy. Pro vrácení do výběru skladeb klikněte `Zavřít` nebo zmáčkněte `2` či `Esc`.

Kliknutím na `Random` nebo zmáčknutím `F2` vám hra **náhodně vybere beatmapu z vaší knihovny.**

*Poznámka: Stisknutím `Shift` + tlačítka `Random` nebo stisknutím `F2` se vrátíte na předešlé mapy vybrané náhodným výběrem.*

![](img/beatmap-options.jpg "Possible commands for a beatmap")

Kliknutím na `Beatmap Options`, stisknutím `F3` nebo kliknutím pravého tlačítka myši na beatmapu zobrazíte **menu možností pro vybranou beatmapu**.

- Stisknutím `1` nebo kliknutím na `Spravovat sbírky` zobrazíte správce Kolekcí — zde můžete spravovat své kolekce, do kterých poté můžete přidávat nebo odebírat obtížnosti nebo celé mapsety beatmap.
- Stisknutí `2` nebo kliknutí na `Vymazat...` vám dovolí vymazat \[1\] vybrané beatmapy, jinými slovy *celý mapset*, \[2\] vybrané obtížnosti, nebo \[3\] **vymazání VŠECH VIDITELNÝCH beatmap**.
  - Pamatujte že vymazané beatmapy jsou přesunuty do koše.
- Stisknutím `3`nebo kliknutím na `Odstranit z ještě nehraných` označíte nehranou beatmapu za hranou (změní se její barva z růžové na oranžovou).
- Stisknutím `4` nebo kliknutím na `Vymazat všechna lokální skóre` vymažete všechny lokální záznamy na beatmapě.
- Stisknutím `5` nebo kliknutím na `Změnit` otevřete vybranou obtížnost beatmapy v osu! editoru.
- Stisknutím `6`, `Esc` nebo kliknutím na `Zrušit` pro vrácení do výběru skladeb.

Kliknutím na **váš uživatelský panel** dostanete přístup do **menu uživatelských možností**.

Kliknutím na **[osu! cookie](/wiki/Client/Interface/Cookie)** **spustíte vybranou beatmapu**.

## Obrazovka výsledku

![](img/results-osu.jpg "Accuracy in osu!")

Toto je obrazovka s výsledky, která se zobrazí po dokončení beatmapy. Váš online výsledek zobrazíte posunutím obrazovky dolů nebo kliknutím na tlačítko "Online Ranking".

Níže jsou výsledkové obrazovky ostatních herních módů.

![](img/results-taiko.jpg "Accuracy in osu!taiko")

![](img/results-mania.jpg "Accuracy in osu!mania")

![](img/results-catch.jpg "Accuracy in osu!catch")

### Rozšířená obrazovka výsledku

![](img/extended-results-screen.jpg "An example of an online osu! score")

Toto je váš online žebříček. Zde se dostanete potažením výsledkové obrazovky dolů. Na místní výsledkové tabuli se objeví vaše jméno a skóre.

- \[1\] Uživatelský panel. Ukazuje [performance points (pp)](/wiki/Performance_points), globální rank, celkové skóre, celkovou [přesnost](/wiki/Gameplay/Accuracy), a ukazatel úrovně.
- \[2\] `Uložit záznam do Složky záznamů`: Na svůj záznam se můžete podívat přes lokální žebříček, nebo běžte do složky `Replays` a na záznam klikněte dvojklikem.
- \[3\] `Přidat do oblíbených`: Přidejte beatmapu do svých oblíbených, které jsou na vaši osu! stránce v kategorii `Beatmapy`.
- \[4\] Lokální žebříček: Všechny vaše výsledky jsou uloženy na vašem počítači. Pro jejich zobrazení běžte do [výběru skladby](#song-select) a vyberte `Lokální` z nabídky nad žebříčkovou tabulkou.
- \[5\] `Beatmap Ranking`. Dostupné pouze pro beatmapy s online žebříčky ([kvalifikované](/wiki/Beatmap/Category#qualified), [hodnocené](/wiki/Beatmap/Category#ranked), nebo [loved](/wiki/Beatmap/Category#loved)). Pro zobrazení musíte být online. Více informací níže.
- \[6\] `Overall Ranking`. Dostupné pouze pro beatmapy s online žebříčky. Pro zobrazení musíte být online. Více informací níže.
- \[7\] Informace o beatmapě, počet zahrání a úspěšnost ostatních hráčů.
- \[8\] Uživatelské hodnocení beatmapy. Rozhodněte se podle sebe, zda se vám mapa líbila či nikoli. Pokud se nemůžete rozhodnout bude nejlepší nechat prázdné.
- \[9\] Kliknutím zde, nebo stisknutím `Esc`, se vrátíte do výběru skladeb.

---

Kategorie na panelu hodnocení jsou následující:

| Kategorie | Hodnocení Beatmapy | Celkové Hodnocení |
| :-: | :-- | :-- |
| `Celkově` | Pozice na žebříčku beatmapy. Skóry s [módy](/wiki/Game_modifier) se zobrazují na stejném žebříčku. | [Globální hodnocení](/wiki/Ranking#performance-points-ranking) proti všem na světě. |
| [`Přesnost`](/wiki/Gameplay/Accuracy) | S jakou přesností jste beatmapu zahráli. Počítá se pouze v případě kdy zlepšíte vaše poslední skóre. | Vážený průměr přesnosti vašich nejlepších skórů. |
| `Max Combo` | Největší combo na mapě kterou jste hráli. | Největší combo ze všech map které jste hráli. |
| [`Hodnocené skóre`](/wiki/Gameplay/Score/Ranked_score) | Váš [nejlepší výsledek](/wiki/Gameplay/Score/Ranked_score) na beatmapě. | Součet skóre ze všech hodnocených map které jste hráli. Každá mapa se přičítá pouze jednou. |
| [`Celkové skóre`](/wiki/Gameplay/Score/Total_score) | Nezapočítáváno, jelikož nemění vaši pozici v Globálním ranku. | Stejné jako hodnocené skóre, ale bere v potaz všechny beatmapy dostupné na osu! stránce, včetně nedohraných nebo neúspěšných beatmap. Toto se započítává do vaší [úrovně](/wiki/Gameplay/Score/Total_score#level). |
| [`Performance`](/wiki/Performance_points) | Hodnota [Neváženého pp](/wiki/Performance_points#why-didn't-i-gain-the-full-amount-of-pp-from-a-map-i-played?) kterou byste dostali z beatmapy. | Celkový počet pp, a jakou hodnotu měl výsledek. |

### Medaile

*Hlavní stránka: [Medaile](/wiki/Medals)*

![](img/medal-unlock.jpg "Unlocking a medal")

Pokud se spolu sejde několik podmínek, můžete dostat medaili.
