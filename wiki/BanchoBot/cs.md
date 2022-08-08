---
tags:
  - bancho
  - server bot
  - commands
  - announcements
---

# BanchoBot

*Další významy viz. [Bancho (rozcestník)](/wiki/Disambiguation/Bancho).*

![Uživatelská karta BanchoBota](img/BanchoBot.jpg "Uživatelská karta BanchoBota")

**BanchoBot** (někdy nazýván *Bancho*) je onlinový chatovací bot vytvořený pro osu!, který v herním chatu pomáhá lidem oznamováním zpráv o hře (např. celkové playe, opakování mapy, atd.) a odpovídáním na určité příkazy. Byl naprogramovaný uživatelem [Echo](https://osu.ppy.sh/users/431) a je poskytovatelem [Bancho IRC](/wiki/Community/Internet_Relay_Chat) (Internet Relay Chat).

BanchoBot má také svůj vlastní [osu! profil](https://osu.ppy.sh/users/3) a [Twitter účet](https://twitter.com/banchoboat).

## Příkazy

*Seznam příkazů v herním klientovi viz. [Chatovací Konzole](/wiki/Client/Interface/Chat_console#commands-list)*

BanchoBot může odpovídat hráči na jeho příkazy pomocí speciálně napsaných zpráv v chatu. Všechny příkazy BanchoBota začínají vykřičníkem (`!`), za kterým je název příkazu (bez rozlišování velkých a malých písmen a mezer). Tyto příkazy mohou být použity v chatovacích kanálech a soukromých zprávách s BanchoBotem.

Pokud klasický uživatel pošle příkaz do veřejného chatovacího kanálu, ostatní uživatelé ho neuvidí a odpověď mu přijde do soukromé zprávy s BanchoBotem. Uživatelé mohou také použít `/bb` v herním klientovi, aby automaticky otevřeli záložku s BanchoBotem a poslali příkaz ihned.

Seznam všech příkazů BanchoBota:

- [Pomoc](#help)
- [Roll](#roll)
- [Statistiky](#stats)
- [Kde](#where)
- [FAQ](#faq)
- [Nahlásit](#report)

### Pomoc

```
!help
```

`!help` ukáže seznam všech dostupných příkazů BanchoBota. Ukázka použití tohoto příkazu:

```
13:00 pippi: !help
13:00 BanchoBot: Standard Commands (!COMMAND or /msg BanchoBot COMMAND):
13:00 BanchoBot: WHERE <user>
13:00 BanchoBot: STATS <user>
13:00 BanchoBot: FAQ <item>|list
13:00 BanchoBot: REPORT <reason> - call for an admin
13:00 BanchoBot: REQUEST [list] - shows a random recent mod request
13:00 BanchoBot: ROLL <number> - roll a dice and get random result from 1 to number(default 100)
```
*Upozornění: Příkaz `!request` již není BanchoBotem podporován.*

### Roll

```
!roll <argument>/<číslo>
```

`!roll` vylosuje náhodné číslo od 1 do vybraného čísla. Pokud není žádné číslo specifikováno, nebo není dán žádný argument, je maximální hodnota 100. Ukázky použití toho příkazu:

```
13:00 pippi: !roll 1000
13:00 BanchoBot: pippi rolls 109 point(s)
```

```
13:01 pippi: !roll probability of failure
13:01 BanchoBot: pippi rolls 75 point(s)
```

### Statistiky

```
!stats <jméno>
```

`!stats` zobrazí statistiky a aktuální status zadaného uživatele. Výsledek závisí na [herním módu](/wiki/Game_mode), který zadaný uživatel naposledy hrál, i když BanchoBot neukáže, ze kterého herního módu statistiky jsou. Pokud je zadán uživatel, který nikdy osu nehrál, BanchoBot odpoví `User not found` ("Uživatel nenalezen"), i přestože uživatel existuje. Ukázka použití tohoto příkazu:

```
13:01 pippi: !stats peppy
13:01 BanchoBot: Stats for peppy:
13:01 BanchoBot: Score: 427,514,691 (#94718)
13:01 BanchoBot: Plays: 7348 (lv66)
13:01 BanchoBot: Accuracy: 87.13%
```

Celkově je 7 statusů, které mohou být zobrazeny pomocí příkazu `!stats`: Editing, Idle, Lobby, Modding, Multiplayer, Multiplaying a Playing. Ukázka použití tohoto příkazu pro uživatele s dostupným statusem:

```
13:01 pippi: !stats peppy
13:01 BanchoBot: Stats for peppy is Playing:
13:01 BanchoBot: Score: 427,514,691 (#94718)
13:01 BanchoBot: Plays: 7348 (lv66)
13:01 BanchoBot: Accuracy: 87.13%
```

### Kde

```
!where <jméno>
```

`!where` ukazuje aktuální polohu zadaného uživatele. Ve výchozím stavu ukazuje tento příkaz pouze uživatelův stát, pokud má však povolené `Zobrazte město, kde se právě teď nacházíte ostatním`, ukáže i jeho aktuální město. Ukázka použití tohoto příkazu:

```
13:02 pippi: !where Ephemeral
13:02 BanchoBot: Ephemeral is in Australia
```

### FAQ

```
!faq <argument>
```

```
!faq list
```

`!faq` zobrazí obsah argumentu, případně může být zadán speciální argument `list`, který zobrazí seznam všech dostupných argumentů. Ve výchozím stavu BanchoBot odpoví v Angličtině, je ale možné obdržet odpověď v jiném jazyce použitím předpony před argumentem, která obsahuje [dvoupísmenný kód](/wiki/Article_styling_criteria/Formatting#locales) daného jazyka. Ukázka použití tohoto příkazu:

```
13:03 pippi: !faq peppy
13:03 BanchoBot: peppy is the lead developer and indeed, the creator of osu! and handles most of the project himself.
```

```
13:04 pippi: !faq ru:lines
13:04 BanchoBot: Умещайте свои мысли в меньшее количество строк, чтобы не получить сайленс.
```

### Nahlásit

*Informace o tom, co je vhodné nahlásit viz. [Nahlášování špatného chování](/wiki/Reporting_bad_behaviour).*

```
!report <uživatel> <důvod>
```

`!report` upozorní [Globální Moderátorský Tým](/wiki/People/The_Team/Global_Moderation_Team) o nesprávném chování zadaného uživatele. Pokud má uživatel ve svém jméně mezery, nahraďte je podtržítkem (např. `vazne huste jmeno` se změní na `vazne_huste_jmeno`). Pokud chcete nahlásit moderátora, zkontaktujte [tým podpory účtu](/wiki/People/The_Team/Account_support_team#support@ppy.sh). Ukázka nahlášení klasického uživatele pomocí BanchoBota:

```
13:10 pippi: !report flyte spamming in #japanese
13:10 BanchoBot: Chat moderators have been alerted. Thanks for your help.
```

## Trivia

- Uživatelská stránka BanchoBota má "Zde od počátku" jako jeho datum připojení.
  - Oficiální datum připojení BanchoBota je 22:09:14 UTC-5, 27 Srpen 2007