<!-- TODO: dated images and links, formatting problems, writing could be done better instead of all these lists. I removed the `needs_cleanup` tag because this still details the Chat Console pretty well. -->

# Chatová Konzole

Z většiny obrazovek v osu! jste schopni pomocí stisknutí `F8` nebo kliknutím na `Show Chat` zobrazit v dolní třetině obrazovky Chatovací Konzole.

![Chat Console](img/Chatconsole1.png "Chat Console")

- Seznam záložek je seznam dostupných kanálů. Kliknutím na záložku se přesunete do příslušného kanálu. Kliknutím na žluté tlačítko *+* zobrazíte seznam dalších přístupných kanálů.
- Barvy uživatelů znamenají:

| Barva | Kdo/co to je? |
| :-- | :-- |
| **Bílá** | Vy |
| **Bledě žlutá** | Standardní uživatelé |
| **Žlutá** | [osu!supporteři](/wiki/osu!supporter) |
| **Červená** | [Moderační tým](/wiki/People/The_Team/Global_Moderation_Team) nebo [Tým nominátorů beatmap](/wiki/People/The_Team/Nomination_Assessment_Team ) member |
| **Zelená** | Zpráva obsahuje vaše jméno nebo slova která jste si vybrali vyvolá takzvaný [highlight](Highlight). Kopie této zprávy se také objeví v přiděleném kanále, `#highlight`, který obsahuje všechny tyto zprávy. |
| **Modrá** | Soukromá zpráva |
| **Azurová** | [peppy](https://osu.ppy.sh/users/2), tvůrce a dosavadní vývojář osu! |
| **Růžová** | [BanchoBot](/wiki/BanchoBot) |

- Kliknutím na `Show Ticker` se nové zprávy zobrazují na dolní části obrazovky, a to i přes to že je Chatová konzole zavřená.
- Možnost `Auto-Hide` automaticky Chat během hrací zavře (s výjimkou začátku a konce beatmap nebo přestávek).
- Tlačítko `Hide Chat` nebo stisknutí `F8` schová otevřenou konzolu.

*Poznámka: Všechna tlačítka zmíněná výše jsou v levém dolním rohu Chatové Konzole.*

## Rozšířená Chatová Konzole

*[osu!academy](/wiki/Community/Video_series/osu!academy) tuto část vysvětlila v [Episodě 6 (6:52)](https://www.youtube.com/watch?v=cyYRl-a5xII) společně s [Multiplayer](/wiki/Client/Interface/Multiplayer).*

Stejně jako u Chatové Konzole jste schopni vyvolat Rozšířenou Chatovou Konzolu stisknutím `F9` nebo zmáčknutím tlačítka `Online Users`, které se nachází v pravém dolním rohu Chatové Konzoly. Společně s Chatovací Konzolou, Rozšířená Chatová Konzole zaplní zbývající místo na obrazovce okny, které zobrazují všechny přihlášené hráče *(tj. ti hráči kteří jsou právě přihlášení do osu! klienta)*.

![Extended chat console](img/Chat_Console-Extended.png "Extended chat console")

Každý hráč zde má svůj panel zobrazující jeho jméno, avatar, celkové hodnocené skóre, rank, přesnost a počet zahrání. Pokud je na panelu kurzor, panel začne zobrazovat jiné informace, tj. hráčovo jméno, rank, avatar, místní čas, časová zóna, země ze které je uživatel přihlášen (podle IP), město a co uživatel dělá (poslední dvě vyžadují schválení uživatelem).

V horní části obrazovky jsou dostupné funkce schopné přihlášené uživatele filtrovat a seřazovat. Tyto čtyři funkce popíši shora dolů a zleva doprava.

V políčku `Filtr` uživatele filtrujete pomocí čtyř filtrů

| Filtr | Efekt |
| :-- | :-- |
|**Všichni**| žádný |
|**Přátelé**| Zobrazí pouze vaše přátele |
|**Poblíž**| Zobrazí hráče blízko vás |
|**Země**| Zobrazí hráče z vaší země|

Kontrolka `Zamknout panely` znemožní uživatelským panelům se pohybovat. 
*Poznámka: tato možnost nebude zobrazovat nově přihlášené uživatele!*

Políčko `Hledat` hledá uživatele podle jejich jména.

Pomocí čtyř ikon herních módů v osu! jste schopni filtrovat uživatele podle jejich preferovaného módu.
 
| Obrázek | Popis |
| :-- | :-- |
| ![Hráč je nečinný](img/Chat_Console-Idle.png "Hráč je nečinný") | Tmavě modrá - Hráč je nečinný. |
| ![Hráč hraje](img/Chat_Console-Playing.png "Hráč hraje") | Šedá - Hráč hraje beatmapu v hře pro jednoho. |
| ![Hráč se dívá](img/Chat_Console-Watching.png "Hráč se dívá") | Světle modrá - Hráč se dívá na záznam nebo někoho sleduje. |
| ![Hráč upravuje beatmapu](img/Chat_Console-Editing.png "Hráč upravuje beatmapu") | Červená - Hráč upravuje svoji beatmapu. |
| ![Hráč testuje beatmapu](img/Chat_Console-Testing.png "Hráč testuje beatmapu") | Fialová - Hráč zkouší hrát beatmapu v editoru. |
| ![Hráč odesílá beatmapu](img/Chat_Console-Submitting.png "Hráč odesílá beatmapu") | Tyrkysová - Hráč odesílá (buď ji odesílá nebo aktualizuje) jeho beatmapu. |
| ![Player is modding a beatmap](img/Chat_Console-Modding.png "Player is modding a beatmap") | Green - Modding or editing someone else's beatmap. |
| ![Player in Multiplayer](img/Chat_Console-Multiplayer.png "Player in Multiplayer") | Brown - User is in multiplayer, but not playing. |
| ![Player is playing in Multiplayer](img/Chat_Console-Multiplaying.png "Player is playing in Multiplayer") | Yellow - Currently playing in multiplayer. |
| ![Player is Afk](img/Chat_Console-Afk.png "Player is Afk") | Black - Inactive or away from keyboard (afk). |
| ![Player is connected via IRC](img/Chat_Console-IRC.png "Player is connected via IRC") | Dark Blue without content - Player is not in-game, but signed in to an IRC client or stats are not available. |

Clicking on any user panel brings up an options screen.

![User panel options](img/Chat_Console-Userpaneloptions.jpg "User panel options")

Press the number or click the bar to activate:

1. `Start Spectating`: If the user is playing a beatmap and you have the beatmap, you can watch them while they play. Your name will be in their Spectators list.
2. `View Profile`: Opens the player profile webpage in your browser.
3. `Start Chat`: Opens a private chat tab with the user.
4. `Invite to game`: (If you are in the Multi room) Request the user to come to your room.
5. `Add (Remove) as Friend`: Adds (Removes) the user at your friends list
6. `Report User`: Report the user for misbehaviour. Should never be used unless stated otherwise. You can report a user in-game for a number of things, but also on the web, like the forums.
7. `Ignore User`: Any chat entry by the user will not appear in your chat console.
8. `Close`: Closes the panel.

## Commands list

### /help

| Command | Effect | Example | BanchoBot response |
| :-- | :-- | :-- | :-- |
| `/addfriend [user]` | Add `[user]` to your friends list. | `/addfriend Amigo` | You are now friends with Amigo. |
| `/delfriend [user]` | Remove `[user]` from your friends list. | `/delfriend Amigo` | You are no longer friends with Amigo. |
| `/away [message]` | Sets an away message (sent to users PMing you). Leave message blank to cancel. | `/away I am John Smith.` | You have been marked as being away: I am John Smith. When Amigo /msg John Where are you~? BanchoBot: I am John Smith. |
| `/bb` | Sends a message to Bancho to execute a command like `!stats [user]` | `/bb !stats Uan` | \[15/11/12\] Stats for [Uan](https://osu.ppy.sh/users/147623): Score: 47,323,299,680 (#1) Plays: 176293 (lv102) Accuracy: 98.95% |
| `/chat [user]` | Open a new chat tab with specified user. | `/chat Amigo` | (Amigo tab is opened) |
| `/clear` | Clears the current chat buffer. | `/clear` | (Clears basically everything on the current tab) |
| `/ignore [user][@chp]` | Ignore all messages from specified user for this session. By adding an @ followed by the letters, c, h, and/or p, you may ignore them in chat, [highlights](Highlight), or PMs respectively. | `/ignore Amigo@chp` | BanchoBot: You will no longer hear Amigo {chat} {highlights} {PM} (Your chat console is set to: ignore any text written by Amigo \[c\], any possible text highlighting you by Amigo \[h\] any Private Message sent to you by Amigo \[p\]) |
| `/j [channel]` or `/join [channel]` | Joins the specified channel | `/join #lobby` | (#lobby tab is opened) |
| `/p` or `/part` | Leaves the current channel you're parting or leaving. | `/part` | n/a |
| `/unignore [user]` | Stop ignoring this user for this session. | `/unignore Amigo` | You may now hear Amigo. (Your chat console will allow any comment made by Amigo available to your chat console) |
| `/me [action]` | Perform a third-person action. | `/me is at home` | * John is at home |
| `/msg [user] [msg]` | Send a private message to `[user]`. | `/msg Amigo I am sick at home.` | (At Amigo tab) John: I am sick at home. |
| `/np` | Print to chat the current song you are listening to or playing. | `/np` | (If playing) * John is playing [Peter Lambert - osu! tutorial \[Gameplay Basics\]](https://osu.ppy.sh/beatmapsets/3756#osu/22538) |
| `/reply` or `/r` | Reply to the last received private message. | `/r Do you know any good doctor?` | (At Amigo tab) \[Previous comments\] John: I am sick at home. Amigo: Really? John: Do you know any good doctor? |
| `/savelog` | Saves current chat tab to a text file. | `/savelog` | (A folder called "Chat" will be created at the osu! directory which will contain all the future chat tab saves) |
| `/watch [user]` | Start spectating `[user]`. | `/watch Amigo` | * Started spectating Amigo. (When Amigo plays a beatmap that you have, you will spectate his play \[after some buffering\] with your name on the left of Amigo's screen) |
| `/nopm` | Toggle to allow private messages either from everyone or friends only | `/nopm` | (A pop-up banner will appear at the centre detailing you are allowing everyone/friends only for private messages) |
| `/invite [user]` | Invites `[user]` to the multiplayer room along with the link. | `/invite Nathanael` | * Nathanael has been invited to the game |

### /keys

| Keyboard keys | Effect |
| :-- | :-- |
| `Page Up` / `Page Down` | Scroll the chat window. You may also use the mouse-wheel. |
| `Tab` | Auto-complete currently typing nickname. |
| `F8` | Toggle chat console. |
| `F9` | Toggle extended chat console. |
| `Ctrl` + `C` / `V` | Copy/Paste. |
| `Alt` + `0` - `9` | Switch to respective tab. |
