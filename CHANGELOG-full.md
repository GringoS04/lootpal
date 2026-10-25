# Changelog, full history

Every upload of LootPal up to 0.2.75, step by step, newest first. The short version is in [CHANGELOG.md](CHANGELOG.md).

LootPal is in **early alpha**. The middle number marks milestones (for example sync between phones, or equipment). The last number counts uploads within a milestone. 1.0 is the full companion, tested at the table.

---

## 0.2.75 · 2026-10-25

### Changed
- Cleanup, no visible changes. Removed leftovers from features that are gone (sessions, the old undo row, the coin-settings shortcut, unused styles) and 24 unused translations. New tables no longer store session data. Older tables keep their session names in the ledger.
- README: the receipt section now covers Where, the capital-letter tags, the Customize switches and the fresh receipt per payment. Ledger and Export now say "day" instead of "session".

---

## 0.2.74 · 2026-10-25

### Added
- **Customize → Receipt → Receipts**: switch receipts off for the whole table. The Receipt button disappears, and payments go in the ledger with just the amount. On by default. The quick-tags switch sits below it and hides while receipts are off.

---

## 0.2.73 · 2026-10-25

### Added
- **Customize → Receipt**: switch the quick tags under the receipt fields on or off. On by default, one setting for the whole table.

---

## 0.2.72 · 2026-10-25

### Fixed
- The receipt no longer carries over: switching to another character, between Pay and Receive, or between Give and Take now starts with an empty receipt. Before, a tag you'd tapped without paying (say *Bribe*) stayed in the To line.
- A place saved by an older version no longer shows up again.

---

## 0.2.71 · 2026-10-25

### Changed
- Quick pick *Room & board* is now *Lodging* (German: *Unterkunft*).

---

## 0.2.70 · 2026-10-25

### Changed
- Quick-pick tags under the receipt fields are shown in capitals (CLIENT, MERCHANT, TAVERN). What they fill in stays as before (*Client*).

---

## 0.2.69 · 2026-10-25

### Changed
- **Where** is back on the players' receipts too. It still starts empty for each payment.

---

## 0.2.68 · 2026-10-25

### Changed
- Back to *Everyone else*, *All players*, *Split in party*, *Room & board*, *Fallen foe* (undoes 0.2.67).

---

## 0.2.67 · 2026-10-25

### Changed
- All tags in English now capitalize every main word: *Everyone Else*, *All Players*, *Split in Party*, *Room & Board*, *Fallen Foe*.

---

## 0.2.66 · 2026-10-25

### Changed
- **Where** is on the GM's receipt only, and no longer stays filled in: like the other fields, it is empty again after each payment. Players' receipts don't show it.

---

## 0.2.65 · 2026-10-25

### Changed
- Quick picks keep their capital letter when tapped, for players and the GM alike: the field and the ledger now say *Toll*, *Gear*, *Loot* (it was *toll*, *gear*, *loot* in English).

---

## 0.2.64 · 2026-10-25

### Added
- **Where** has quick picks too: recent places first, then *Town*, *Tavern*, *Market*, *Road*, *Wilds*, *Dungeon*.
- GM quick picks: *Merchant* and *Found* (source), *Sale* (what), *Upkeep* and *Lost* (reason).

### Changed
- GM quick picks reordered so the most common come first. Source: Fallen foe, Chest, Hoard, Patron, Merchant, Found. What: Loot, Reward, Payment, Bounty, Sale, Salary. Reason: Upkeep, Tax, Toll, Fine, Theft, Lost.

### Removed
- *Treasure* (overlapped with Loot and Hoard).

---

## 0.2.63 · 2026-10-25

### Added
- GM quick pick **Payment** (for a job done), between Reward and Bounty. German: *Bezahlung*.

---

## 0.2.62 · 2026-10-25

### Added
- **Quick picks under every receipt field**, one tap to fill in, tap again to clear:
  - Paying: *To* Merchant, Innkeeper, Blacksmith, Temple, Guard · *For* Gear, Room & board, Healing, Drinks, Bribe
  - Receiving: *From* Client, Merchant, Chest, Fallen foe · *For* Sale, Job, Wages, Winnings
  - GM giving: *Source* Chest, Fallen foe, Patron, Hoard · *What* Treasure, Loot, Reward, Bounty, Salary
  - *Where*: the places used most recently
- All in German too.

---

## 0.2.61 · 2026-10-25

### Changed
- **Undo per payment.** Each payment now remembers exactly which coins moved and which deeds it earned, so one payment can be taken back without touching the ones after it. In the Ledger, a small **↶ Undo** sits under the entry: a player sees it on their own newest payment, the GM on any of the last ten. If the coins have already been spent, undo is refused with a message. The big Undo bar at the top of the Ledger is gone.
- Payments made before this version can only be undone as before (the latest one).

---

## 0.2.60 · 2026-10-25

### Fixed
- The GM's quick picks (Treasure, Loot…) sit right under *What* / *Reason* again, above *Where*.

---

## 0.2.59 · 2026-10-25

### Added
- A player's book also names the **biggest haul**: the largest single sum received (loot, a reward, a salary, a sale), with what it was, e.g. *Biggest haul: treasure, 2g.*

### Fixed
- German quick picks keep their capital letter in the ledger (*für Schatz*, not *für schatz*).

---

## 0.2.58 · 2026-10-25

### Changed
- **Days instead of sessions.** Every payment is stamped with its date, and the ledger groups by game night automatically (*Sat, 25 Oct · +12g −3g*; anything before 6 am counts as the night before). No button to press. Older entries keep their session headings.
- **Where** in the receipt: a sticky place. Type *Saltmarsh* once and every payment from then on is listed under it, until someone changes it. In the ledger, places are small sub-headings within the day; Export follows the same structure.
- The *+ Session or place* button, its form and the ✎ renaming are gone.

---

## 0.2.57 · 2026-10-25

### Changed
- The whole list of entries folds away with its own heading (**Entries · 12**), so the deeds and your book are one tap away. Each device remembers it.
- Session headings no longer fold one by one. The list shows the newest 50 entries, with **Show 50 more** for older ones.

---

## 0.2.56 · 2026-10-25

### Changed
- **The Ledger stays short:** the current session is open, older sessions are folded to their heading (name, date, totals). Tap a heading to open or fold it. More than 12 sessions: the oldest wait behind **Show older**.
- The ledger keeps the last **2,000** payments instead of 200, so totals, the books and Export cover a long campaign.

---

## 0.2.55 · 2026-10-25

### Changed
- Export includes every session or place heading, even one without payments, so a place you passed through still shows up in the recap.

---

## 0.2.54 · 2026-10-25

### Changed
- Receipt fields look like receipt lines: the label sits inside the field (*To ____*, *For ____*), in the same pill shape as the *To* line and the tags, with the same left edge. The entries line up with each other.

---

## 0.2.53 · 2026-10-25

### Changed
- Everyone can add a session or place, but only the GM can rename one: the ✎ appears only while the GM is chosen.

---

## 0.2.52 · 2026-10-25

### Fixed
- The receipt's labels are vertically centred on their fields again (the first one sat too high).

---

## 0.2.51 · 2026-10-25

### Changed
- **Receipt labels** are short, like a real receipt, and follow one pattern: players paying **To** · **For**, receiving **From** · **For**; the GM giving **Source** · **What**, taking **Reason**. The examples stay in the fields. The fields got wider.

---

## 0.2.50 · 2026-10-25

### Changed
- A player's book is now one sentence instead of six tiles, e.g. *Player 1 has earned 12g 4s and spent 8g 3s. Biggest purchase: a longsword, 1g.* Folded by default.

---

## 0.2.49 · 2026-10-25

### Changed
- The receipt's second field fits what's happening: *For what?* for players, *What is it?* when the GM gives (Treasure, Loot, Reward…), *Why?* when the GM takes (Tax, Fine…).

---

## 0.2.48 · 2026-10-25

### Added
- **A player's own book** in the Ledger: lifetime totals for the character you're looking at. Earned, spent, from and to companions, the biggest purchase (with what it was for) and the number of payments. Folds away like the deeds.

### Changed
- The Game Master's book is no longer shown in the Ledger. It stays on the GM's purse screen.

---

## 0.2.47 · 2026-10-25

### Changed
- In the Ledger, the entries now come right below their tools (filter, + Session or place, Export, Undo). Deeds and the Game Master's book follow after the entries, each with its own heading.

---

## 0.2.46 · 2026-10-25

### Changed
- The deeds in the Ledger fold away with a tap on their heading. Each device remembers it.

---

## 0.2.45 · 2026-10-25

### Changed
- **+ Session or place:** the button now makes clear a heading can be a game night or a place, and it's there for everyone, not only the GM. The name field starts filled with *Session 3*: keep it or type over it. The button below is now **Add to ledger**. Everyone can rename a heading with ✎.

---

## 0.2.44 · 2026-10-25

### Changed
- Sessions are back in the Ledger: **+ Session 3** sits next to Export (GM only). It opens a name field (optional) with **Start session 3**, so a session is named as it begins. A ✎ beside each session's name renames it later. The session field in the Game Master's book is gone.

---

## 0.2.43 · 2026-10-25

### Changed
- Sessions live in one place, the Game Master's book: *Now playing: session 2*, a plain name field (saves as you type), and **Start a new session**. The button in the Ledger and tap-to-rename on the session headings are gone.

---

## 0.2.42 · 2026-10-25

### Changed
- **Only the Game Master starts and names sessions.** The Game Master's book now begins with *Now playing*: the current session's name and date, plus **+ Session 3**. In the Ledger, the button and the editable names only appear while the GM is chosen. Players see the sessions but can't change them.

---

## 0.2.41 · 2026-10-25

### Changed
- **Name of the NPC tag** moved from Party to **Table**, next to the table name; both are names for your campaign. The backup part of the Table tab got its own heading.

---

## 0.2.40 · 2026-10-25

### Added
- **Named sessions.** A new session asks for a name straight away (optional, e.g. *The heist at Saltmarsh*). Tap any session's name to rename it; left empty, it's *Session 2* and so on.

### Changed
- The ledger switch reads *Everyone* / *Only Player 1*.
- *Copy text* is now **Export**: it shows the whole ledger as text, with **Copy** and **Save as a file** (.txt).

---

## 0.2.39 · 2026-10-25

### Changed
- **Customize** is back in the bottom menu, between Party and Table: **Ledger · Party · Customize · Table**. The button in the top bar stays, and both show when Customize is open.

---

## 0.2.38 · 2026-10-25

### Added
- **Sessions in the ledger.** Tap **+ Session 2** at the start of a game night. Entries are grouped by session, each with its date and what came into the party and went out. Existing tables start in session 1, with every entry so far in it.
- **Everyone or one character:** a switch at the top of the ledger shows all entries, or only those involving the current character (with that character's totals per session).
- **Copy text:** the whole ledger as plain text, grouped by session, for campaign notes.

### Changed
- The bottom menu has three tabs, in order of use: **Ledger**, **Party**, **Table**. *Save & load* is now called **Table** (table name, backups, save code and file, start a new table). Customize opens only from the top bar.

---

## 0.2.37 · 2026-10-25

### Changed
- The NPC tag no longer uses its own blue. Chosen, it lights up gold like any recipient. Its picture is a hooded figure on slate grey, so it's still easy to tell apart from the players. In the *To* line, the NPC's name is written like any other name.

---

## 0.2.36 · 2026-10-24

### Changed
- ✕ (clear the amount) now matches the keyboard sign opposite it: a plain, muted sign instead of a dark round button.

---

## 0.2.35 · 2026-10-24

### Changed
- More breathing room above and below the **Done** button when typing an amount.

---

## 0.2.34 · 2026-10-24

### Changed
- The keyboard sign for typing an amount moved to the left edge of the amount line, mirroring ✕ on the right. The number and its coins are exactly centred again. The sign lights up while typing. Tapping the number still works too.

---

## 0.2.33 · 2026-10-24

### Changed
- When the GM takes from several players: *Tap a coin or the number · what each one pays*. With nothing counted, the line under the number uses the full width, so it still fits on one line, down to 320px.

---

## 0.2.32 · 2026-10-24

### Fixed
- Split | Each, Receipt and Mixed bag are now always the same height.

---

## 0.2.31 · 2026-10-24

### Changed
- When the GM takes from several players, the line under the number says *Tap coins · what each one pays* again, so it's clear the amount is per player.

---

## 0.2.30 · 2026-10-24

### Changed
- The GM gets the same instruction as players under the number: *Tap a coin or the number*. The chosen tag already shows who it's for. Taking from one player still shows what they have.

---

## 0.2.29 · 2026-10-24

### Changed
- With nothing counted, the line under the number now always explains what to do. Players and the party purse: *Tap a coin or the number* (the status card below already shows what's in the purse). The GM: *Tap coins*, followed by who it's for: *for the party*, *for Player 2*, or *what each one pays* when taking. Taking from one player still shows what they have.
- The line stays on one line on the narrowest phones, so the coins don't jump when you start counting.

---

## 0.2.28 · 2026-10-24

### Changed
- The Game Master's book has the same headline style as the players' status card (small caps, muted), instead of a large serif title.

---

## 0.2.27 · 2026-10-24

### Changed
- The Customize button in the top bar behaves like *Sound on*: lit while Customize is open, muted while it's closed, with no extra frame or glow.

---

## 0.2.26 · 2026-10-24

### Changed
- **The 123 button is gone: tap the number to type an amount.** A small keyboard sign beside the number shows it can be tapped. While typing, the number gets a soft frame, and tapping it again closes the fields.
- Until you've typed an amount once, the line under the number says *Tap a coin, or the number to type*.
- The amount line now holds just the number, plus ✕ while something is counted.

---

## 0.2.25 · 2026-10-24

### Removed
- The round ↶ undo button on the purse. It shared its spot with ✕, so a quick double tap could clear the amount and then undo the previous payment by accident.

### Changed
- The message after each payment, with its Undo button, now stays for six seconds instead of four. Later mistakes can still be undone in the Ledger.

---

## 0.2.24 · 2026-10-24

### Changed
- **Customize moved to the top bar**, next to *Sound on*: a sliders icon with "Customize" (just the icon on narrow phones). It opens the Customize tab and lights up while it's open. The pencil next to the amount is gone.
- The amount now has just two round buttons, level with the number: 123 on the left, ✕ or ↶ on the right.

---

## 0.2.23 · 2026-10-24

### Changed
- The GM's quick picks (Treasure, Loot…) now sit below *For what?*, the field they fill in.
- New quick pick when giving: **Salary**.

---

## 0.2.22 · 2026-10-24

### Changed
- **The receipt moved below the coins.** The round receipt button next to the amount is gone. A **Receipt** button now sits between Split | Each and Mixed bag: always for the GM, inside the *To* line for players, and on its own when receiving. On phones it shows as a small icon with its name underneath, so all three fit on one line.
- For players, the *To* line shows what's in the receipt when folded, e.g. *To the blacksmith · for a longsword*. Folding the line folds the receipt too; what's written stays.
- The 123 button moved up to the top left of the amount.

---

## 0.2.21 · 2026-10-24

### Changed
- **Who gets it** moved out of the receipt. Players now see a compact line below the coins, *To NPC*, in the same place the GM picks players. Tap it to open the tags (Everyone else, players, Split | Each, Mixed bag). It shows the choice at a glance, for example *To Everyone else (2) · Split*, and folds away after each payment.
- The receipt now only holds what goes into the ledger: which NPC, and what for.

---

## 0.2.20 · 2026-10-24

### Added
- **Players can pay several companions at once.** In the receipt, tap **Everyone else** or hold a name to add more players. **Split** shares the amount (what doesn't divide evenly stays in your purse), **Each** gives the full amount to every one of them. Only players can be picked together, not the GM or the party purse.
- **Mixed bag for players.** When paying companions, pay with a random mix of your own coins worth exactly the amount, without change when possible.
- **The Game Master's book folds away** with a tap on its title. Each device remembers it.

### Changed
- The GM's **Whole party** tag is now called **All players**.

---

## 0.2.19 · 2026-10-24

### Added
- **Mixed bag when taking.** The GM's Mixed bag switch now also shows on **Take**, in the same place as on Give. It takes a random mix of the coins each player holds, worth exactly the amount, without change. If no exact mix is possible (for example 5 copper from someone with only silver), LootPal takes it the usual way, with change. The ledger shows which coins were taken.

---

## 0.2.18 · 2026-10-23

### Added
- New top wealth title: **Filthy rich**, from 1000 gold. Tables still on the standard ladder get it automatically; a ladder you've changed stays as it is.

### Changed
- **Start a new table** warns more clearly. The first tap shows a red box listing everything that will be deleted, and that Undo can't bring it back. Tap again within six seconds to go ahead.

---

## 0.2.17 · 2026-10-23

### Changed
- **Deeds are on** for new tables, including **Start a new table**, which also clears every deed already earned. Existing tables keep their setting.

---

## 0.2.16 · 2026-10-23

### Added
- **Worth in any coin.** Under **Customize → Coins**, each coin's worth can be entered in any cheaper coin, for example a platinum worth *20 Gold*. It starts on the base coin, as before. When another coin is picked, the worth in base coins is shown beside it (*= 2,000 c*). Halves work too (*12.5 Silver*), as long as it comes out as whole base coins.

---

## 0.2.15 · 2026-10-23

### Changed
- **Customize:** purse weight moved into **Coins**, below the coins, since each coin's weight is set there too. Wealth titles have their own group, **Wealth**, right below Coins.

---

## 0.2.14 · 2026-10-23

### Removed
- The Deeds tile in the status card. Deeds stay at the top of the Ledger, as before.

---

## 0.2.13 · 2026-10-23

### Added
- **Deeds tile** in the status card, when deeds are on: a star for each deed, how many are earned, and the latest one. Tap it to jump to all deeds in the Ledger.

### Changed
- Mixed bag no longer gets an outline when it's on, so it matches the Split | Each switch beside it.

---

## 0.2.12 · 2026-10-23

### Changed
- **Split | Each** on the Game Master's purse is now a switch like Mixed bag, with *Split* on the left and *Each* on the right. The chosen side is written in bold.

---

## 0.2.11 · 2026-10-23

### Changed
- Tidy-up, no visible changes: removed leftover translations and unused styles from removed features, merged the bottom-tab styles into one place, removed the fallback for the language setting from the app's old name.
- README checked against the app and corrected (colours of open buttons and the receipt marker).

---

## 0.2.10 · 2026-10-23

### Removed
- The GM badge above the GM's picture, and its setting. The thin divider before the GM in the character row stays.

---

## 0.2.9 · 2026-10-23

### Changed
- The GM badge is simpler: flat and pale instead of shiny gold, so it no longer looks like a coin. The d20 is drawn as a line icon.

---

## 0.2.8 · 2026-10-23

### Added
- **GM badge** setting under **Customize → Game Master**: a twenty-sided die (new default), book, crown, eye, quill, or none.

---

## 0.2.7 · 2026-10-23

### Changed
- The Game Master stands out in the character row: a small gold crown sits on their picture (whatever picture they chose), and a thin divider separates them from the players. The crown also shows in the Party tab.

---

## 0.2.6 · 2026-10-23

### Added
- **Character pictures.** Tap a character's picture under **Party** to give them an icon and a colour. Icons: warrior, wizard, cleric, priest, thief, ranger, bard, druid, barbarian, alchemist, sword, dagger, bow, staff, spear, war hammer, plus crown, star, moon, skull, dragon, eagle, lion, shield, crossed swords, key, anchor, tree and fleur-de-lis. The letter or number stays the default. The picture shows in the character row, on the tags and in the Party tab.

---

## 0.2.5 · 2026-10-23

### Added
- **Coin faces.** Each coin can show its letters (as before), a number of your choice, or an emblem struck into the metal: crown, star, sun, moon, heads (profile), tails (wreath), dragon, eagle, lion, tower, shield, crossed swords, key, anchor, ship, tree, wheat, fleur-de-lis, skull, anvil or double axe. Set it under **Customize → Coins → Face**. Emblems also show on the small coins in the amount.

---

## 0.2.4 · 2026-10-23

### Changed
- The pouch is now oiled saddle-brown leather instead of red, in the header and in the app icon, so it sits calmly with the rest of the app.
- New app icon: the pouch on forest-green leather with gold-thread stitching, without the metal frame. It stands out on a home screen and fits every phone's icon shape.

---

## 0.2.3 · 2026-10-23

### Added
- The pouch from the app icon now sits beside the LootPal wordmark in the header.

---

## 0.2.2 · 2026-10-23

### Added
- **Undo on the purse:** a round ↶ button where the ✕ sits while counting. It shows whenever there's something to undo and no amount is being counted. The ledger keeps its undo too.

### Changed
- Undo survives a reload: the last few transactions can still be undone after the page reloads or the phone locks.

---

## 0.2.1 · 2026-10-23

### Added
- Footer credit: By Mapventures · Grímur Fjeldsted · 2026.

---

## 0.2.0 · 2026-10-23

### Added
- New name and logo: **LootPal**.
- **App icon** (leather pouch) for the home screen and the browser tab. Added to the home screen, LootPal opens full screen like an app.
- **German.** LootPal follows the language of the phone or browser, and you can switch under **Customize → Language**. The choice is kept per device. Names LootPal gave (Player 1, Game Master, Gold…) switch with the language; names you chose stay.
- **Status card** under the purse: the character's name with tiles for **Wealth** (total worth as small coins, plus the wealth title) and **Weight** (weight, description, belt bar). With weight off, Wealth takes the full width. More tiles can follow.
- The status card folds away with a tap on its headline. Folded, it still shows the total worth as small coins. Each device remembers it.
- Party purse: **Split in party** tag in the receipt. With no amount counted, it fills in everything in the purse. Tap coins down to share less. What doesn't divide evenly stays in the purse.
- **Table name** in Save & load, for example *Curse of the Crimson Crown*. It's used in the save file's name and shown when loading, so you know which campaign a code or file belongs to.
- **Last backup** reminder: Save & load shows when the last backup was made and how many payments happened since. A small gold dot on the tab means there are payments that aren't backed up yet.
- Small icons on the bottom tabs (Party, Customize, Save & load, Ledger).
- Footer with the version number and a link to this changelog.
- Full documentation in the README, essentials first.

### Changed
- **Receipt** reordered. Players: *To whom?* first (NPC is the default), then *Which NPC?*, then *For what?*. Receiving and the GM: *From who or what?*, the GM's quick picks, then *For what?*. Opening the receipt no longer pops up the keyboard.
- The receipt button shows a character with a pouch. The old receipt icon moved to the Ledger tab.
- **Pay | Receive** moved up next to the character's name, like the GM's Give | Take. The slide bar sits higher, and small phones need less scrolling.
- Pay | Receive and Give | Take are as tall as the name and title together. Pay and Give, the actions used most, are never narrower than Receive and Take, in any language.
- Pay | Receive and Give | Take work like a switch: the highlight glides to the chosen side with a glowing gold border, and you can swipe across the switch as well as tap it.
- Long names shrink a little to fit next to Pay | Receive.
- **Total worth** and **purse weight** moved out of the leather card into the status card. The belt bar runs the full width and fills from green to red.
- Amounts in the line under the amount, the ledger and the GM's book show each coin in its own colour, so *6g 2s 15c* is easier to read.
- **Colours:** gold is kept for the payment itself (Pay | Receive, the selected tag for who gets it, the slide knob), primary buttons, the settings, the logo and deeds. The round buttons (receipt, 123, pencil) glow pale silver when open, and a filled-in receipt shows a ring and a dot. The selected character, Split | Each and Mixed bag are pale parchment; the wealth title and Repeat are muted bronze. Gold, silver and copper on screen now mostly mean coins.
- The **Done** button under the typed amount looks like the Pay | Receive switch (leather with a glowing gold border) instead of solid gold.
- The pencil closes Customize when tapped again.
- **Purse weight** is on for new tables. Existing tables keep their setting.
- New players are added after the other players, before the party purse.
- Removing a coin asks twice. The first tap on × turns it red and explains what happens; tap again within a few seconds to remove.
- **Start a new table** (formerly *Reset example table*) moved from Party to **Save & load**, next to saving, with a reminder to make a save code first.
- Save & load explains that a save holds the whole table: players, purses, coins, settings and the ledger.
- The separate "Share out everything" button on the party purse is gone. *Split in party* does the same job.
- Header logo made smaller.

### Fixed
- iPhone zoomed in when tapping a text field in the receipt and couldn't zoom back. Fields now use a size iPhones don't zoom on.
- Adding a player did nothing in some browsers (including the claude.ai version). The same problem stopped **Done** from closing the typed amount. Both work now, by tap and by Enter.
- German ledger lines read "an der Schmied". The German examples now leave out the article.
- Layout on narrow phones with longer German words (tabs, GM buttons, slide bar).

---

## 0.1.0

First version on GitHub.

- Character purses with stacked coins, tap, hold or drag to count, or type the amount.
- Slide to pay or receive, with automatic change.
- Medieval sounds: coins on an oak table, metal on metal when counting, a leather pouch.
- Game Master with unlimited coffers: give or take, whole party or chosen players, split or each, mixed bag, repeat last payout, the Game Master's book.
- Party purse.
- Receipt: what it's for and who it's to or from, written into the ledger.
- Ledger with undo.
- Custom coins: up to six, with name, worth, colour, shape and weight.
- Wealth titles, purse weight and deeds (optional).
- Starting purse and party settings.
- Save codes and save files.
