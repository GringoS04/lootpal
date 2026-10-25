# Changelog

All notable changes to LootPal, newest first.

LootPal is in **early alpha**. The middle number marks milestones (for example sync between phones, or equipment). The last number counts uploads within a milestone. 1.0 is the full companion, tested at the table.

Each entry describes how things ended up after a day of uploads. Ideas that were tried and dropped the same week are left out. The step-by-step history is in [CHANGELOG-full.md](CHANGELOG-full.md).

---

## 0.2.97 · 2026-10-25

### Changed
- Small cleanup, no visible changes: removed leftovers of the receipt's old "filled in" dot and five unused translations from the quick tags, and updated code notes for the receipt, recent places and the NPC picture.

---

## 0.2.96 · 2026-10-25

### Added
- **Tap the pouch to count out fifty.** Handy for big amounts: three taps make 150. When paying it only works if you can afford a full pouch; when receiving, and for the GM, the pouch is always shown. Holding the pouch keeps adding pouches.

---

## 0.2.95 · 2026-10-25

### Changed
- The pouch beside a coin stack is stamped with **50**, so it's clear each pouch holds fifty coins.

---

## 0.2.94 · 2026-10-25

### Changed
- The Receipt tick box no longer lights up the whole tag when ticked; the tick says it.
- Unticking the receipt clears what was typed in it, so an unticked receipt never ends up in the ledger. Folding the players' *To* line only hides it (the line shows what's in it).

### Removed
- The small dot on the Receipt button for "something is filled in" (there's no hidden content any more).

---

## 0.2.93 · 2026-10-25

### Changed
- **Receipt is a tick box** at the end of the tags: ☐ Receipt when closed, ☑ Receipt (pale, not gold) when open. Since the receipt now stays open, on/off is easy to see at a glance.

---

## 0.2.92 · 2026-10-25

### Changed
- **The receipt stays open** once you open it: after each payment its fields are empty again, but it doesn't close, so a group that likes a detailed ledger taps Receipt once. Close it by tapping Receipt again (or folding the *To* line). Each device remembers.

---

## 0.2.91 · 2026-10-25

### Changed
- The Receipt tag's icon sits on parchment, like a slip of paper, so it's distinct from the players without drawing attention.

---

## 0.2.90 · 2026-10-25

### Changed
- The Receipt tag has the same dark fill and icon circle as the player tags; only its dashed outline sets it apart.

---

## 0.2.89 · 2026-10-25

### Changed
- The NPC tag takes the Game Master's colour (violet unless the GM picked another), since NPCs are the GM's people.

---

## 0.2.88 · 2026-10-25

### Changed
- The small signs around the number are sorted into two rows: the top row is always there (⌨ left, Edit coins right), the row below only when it applies (↻ left, ✕ right while counting). A fresh screen no longer shows the two signs diagonally.

---

## 0.2.87 · 2026-10-25

### Changed
- The NPC tag's picture is a plain head-and-shoulders silhouette instead of the hooded figure, which was hard to read at that size.

---

## 0.2.86 · 2026-10-25

### Removed
- The quick tags under To/From/Source and For/What/Reason, and their switch in Customize. They took a lot of space and rarely matched what happened at the table; *↻ Same as last time* covers the real repeats.

### Changed
- Under **Where**, only the places you've used recently show as tags (no generic *Town*, *Tavern*…), so a new table starts with a calm receipt.

---

## 0.2.85 · 2026-10-25

### Changed
- **The Game Master and the party purse stand out:** the GM's picture starts in violet, the party purse's in teal (players stay leather). Any colour can still be picked under Party. The party purse also gets its own thin divider in the character row, like the GM.

---

## 0.2.84 · 2026-10-25

### Changed
- Clearer **Edit coins** sign: a small stack of coins with a +.

---

## 0.2.82 · 2026-10-25

### Added
- **Edit coins** sign on the right edge of the amount, below ✕: opens Customize at Coins in one tap. Always there, for everyone.

### Changed
- The line under the number now stays between the small signs at the edges instead of running under them. When the GM takes from several players it says *What each one pays*.

---

## 0.2.81 · 2026-10-25

### Changed
- **Receipt** moved to the end of the tags, after the players: the same size as a tag, with a dashed outline so it doesn't look like a recipient. The row below now holds just Split | Each and Mixed bag. On the narrowest phones it shows only the receipt sign, so the slide bar still fits on screen.

---

## 0.2.80 · 2026-10-25

### Added
- **↻ Same as last time**, a small sign below the keyboard sign, for players and the GM. Each character remembers their last payment: amount, who, Split | Each, Mixed bag and the receipt (To, For, Where). One tap fills it all in; you still slide to pay. Only shown while nothing is counted and in the same mode, so it never switches between Pay and Receive or Give and Take.

---

## 0.2.79 · 2026-10-25

### Removed
- The GM's **↻ Repeat** button. Most payouts at the table are one-offs, and *Each* already gives the same amount to every player. The line under the number now always shows the instruction.

---

## 0.2.78 · 2026-10-25

### Changed
- Undo in the Ledger is a small red **×** at the end of the entry instead of a button on its own row. The first tap turns it into *Undo?*, the second undoes.

---

## 0.2.77 · 2026-10-25

### Added
- **The GM can name a game night** in the Ledger: tap the day's heading (✎), type a name, press Enter. The date stays beside the name, e.g. *The heist at Saltmarsh · Sat, Oct 24*. Export uses it too. Players see the name but can't change it.

### Changed
- **Undo in the Ledger asks twice:** the first tap turns the button red, *Tap again to undo*. After four seconds it goes back.

---

## 0.2.76 · 2026-10-25

### Changed
- **Places in the ledger** sit at the end of each line, after a small pin (*Player 1 to Merchant for Gear 📍 Tavern*), instead of as separate headings. Every line is complete on its own, also with the *Only Player 1* filter. Export: *… for Gear · Tavern*.

---

## 0.2.37–0.2.75 · 2026-10-25

### Added
- **Bottom menu in order of use:** Ledger · Party · Customize · Table. *Save & load* is now **Table**: table name, NPC tag name, backups, save code and file, start a new table.
- **Ledger filter:** *Everyone* or *Only Player 1*, with that character's totals.
- **Export:** the whole ledger as plain text, with **Copy** and **Save as a file** (.txt).
- **Days and places.** Every payment is stamped with its date. The ledger groups by game night (anything before 6 am counts as the night before), each heading with what came into the party and went out. Payments with a place are listed under it within the day. Export follows the same structure. Older entries keep their session headings.
- **Where** in the receipt: the place it happened.
- **Quick picks under every receipt field**, one tap to fill in, tap again to clear, shown in capitals:
  - Paying: *To* Merchant, Innkeeper, Blacksmith, Temple, Guard · *For* Gear, Lodging, Healing, Drinks, Bribe
  - Receiving: *From* Client, Merchant, Chest, Fallen foe · *For* Sale, Job, Wages, Winnings
  - GM giving: *Source* Fallen foe, Chest, Hoard, Patron, Merchant, Found · *What* Loot, Reward, Payment, Bounty, Sale, Salary
  - GM taking: *Reason* Upkeep, Tax, Toll, Fine, Theft, Lost
  - *Where*: recent places, then Town, Tavern, Market, Road, Wilds, Dungeon
  - All in German too.
- **Customize → Receipt:** switch receipts off for the whole table (no Receipt button, the ledger shows just the amount), and the quick tags on or off. Both on by default.
- **A player's book** in the Ledger: one sentence with lifetime totals, the biggest purchase and the biggest haul. Folded by default.
- **Undo per payment.** A small **↶ Undo** under an entry takes back just that payment: a player their own newest one, the GM any of the last ten. If the coins are already spent, it says so.
- The list of entries folds away under its heading (**Entries · 12**). It shows the newest 50, with **Show 50 more**. The deeds fold too. Each device remembers both.
- The ledger keeps the last **2,000** payments instead of 200.

### Changed
- **Receipt labels** sit inside the fields, short like a real receipt: players paying **To** · **For**, receiving **From** · **For**; the GM giving **Source** · **What**, taking **Reason**.
- The receipt starts empty for every payment, and again when switching character, Pay | Receive or Give | Take.
- The NPC tag lights up gold like any recipient, with a hooded figure on slate grey instead of its own blue. Its name is set under **Table**.
- The Game Master's book is shown only on the GM's purse screen, not in the Ledger.
- Cleanup of leftover code, styles and translations, no visible changes.

### Removed
- The Undo bar at the top of the Ledger (replaced by undo per payment).

---

## 0.2.19–0.2.36 · 2026-10-24

### Added
- **Players can pay several companions at once.** Tap **Everyone else**, or hold a name to add more players. **Split** shares the amount (what doesn't divide evenly stays in your purse), **Each** gives the full amount to every one of them. Only players can be picked together.
- **Mixed bag for players** paying companions, and for the GM on **Take**: a random mix of coins worth exactly the amount, without change when possible. The ledger shows which coins moved.
- **The To line** for players, below the coins: *To NPC* by default. Tap it to pick who gets it. Folded, it shows the choice and the receipt, e.g. *To the blacksmith · for a longsword*.
- **The Receipt button** sits below the coins, between Split | Each and Mixed bag (inside the To line for players, on its own when receiving).
- **Customize in the top bar**, next to *Sound on*, and lit while open.
- The Game Master's book folds away with a tap on its title.

### Changed
- **Tap the number to type an amount.** A small keyboard sign on the left edge of the amount line shows it can be tapped, mirroring ✕ on the right.
- The line under the number always explains what to do: *Tap a coin or the number*. When the GM takes from several players: *· what each one pays*. Taking from one player shows what they have.
- The GM's **Whole party** tag is now **All players**.
- The message after each payment, with Undo, stays for six seconds.
- The Game Master's book uses the same headline style as the status card.
- Split | Each, Receipt and Mixed bag are always the same height. More room around **Done**.

### Removed
- The 123 button, the pencil, and the round receipt button next to the amount.

---

## 0.2.0–0.2.18 · 2026-10-23

### Added
- New name and logo: **LootPal**, with the pouch beside the wordmark.
- **App icon:** the pouch on forest-green leather. Added to the home screen, LootPal opens full screen like an app.
- **German.** LootPal follows the language of the phone or browser; switch under **Customize → Language**. Names LootPal gave change with the language, names you chose stay.
- **Status card** under the purse, with tiles for **Wealth** (total worth and the wealth title) and **Weight** (weight, description, belt bar). It folds away; each device remembers it.
- **Coin faces:** letters, a number, or an emblem struck into the metal (crown, dragon, eagle, fleur-de-lis and more).
- **Worth in any coin:** a coin's worth can be entered in any cheaper coin, e.g. a platinum worth *20 Gold*.
- **Character pictures:** an icon and a colour per character, under **Party**.
- New top wealth title: **Filthy rich**.
- Party purse: **Split in party**, which shares out everything (or a counted amount).
- **Table name**, used in save files and shown when loading.
- **Last backup** reminder, with a dot on the tab when there are payments not yet backed up.
- Undo survives a reload.
- Icons on the bottom tabs, a footer with version, changelog link and credit, and full documentation in the README.

### Changed
- **Pay | Receive** sits next to the character's name and works like a switch you can tap or swipe, like the GM's Give | Take.
- **Split | Each** on the GM's purse is a switch like Mixed bag.
- Amounts show each coin in its own colour (*6g 2s 15c*). Gold is kept for the payment itself and the main buttons.
- A thin divider separates the Game Master from the players in the character row.
- **Customize:** purse weight sits under **Coins**; **Wealth** has its own group.
- **Deeds** and **purse weight** are on for new tables.
- **Start a new table** moved next to saving and warns with a red box; tap twice to go ahead. It also clears all deeds.
- Removing a coin asks twice.
- New players are added before the party purse.

### Removed
- The party purse's separate "Share out everything" button (*Split in party* does it).

### Fixed
- iPhone zoomed in on receipt fields.
- Adding a player and **Done** did nothing in some browsers.
- German ledger lines ("an der Schmied") and layout on narrow phones with long German words.

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
