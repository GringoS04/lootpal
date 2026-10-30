<p align="center"><img src="lootpal-logo.png" alt="LootPal" width="420"></p>

# LootPal

An interactive coin purse for tabletop RPGs. Count coins with a tap, slide to pay, and let the Game Master hand out treasure. LootPal keeps track of who has what, makes change automatically and writes everything into a ledger.

Everything runs in one file, `index.html`. No server, no account, no installation.

LootPal is in early alpha. See the [changelog](CHANGELOG.md) for what's new.

---

## Contents

**The essentials**

1. [Getting started](#1-getting-started)
2. [Paying and receiving](#2-paying-and-receiving)
3. [The Game Master](#3-the-game-master)
4. [Save your table](#4-save-your-table)

**More detail**

5. [The receipt: who and what for](#5-the-receipt-who-and-what-for)
6. [The party purse](#6-the-party-purse)
7. [The gem bag](#7-the-gem-bag)
8. [Ledger and undo](#8-ledger-and-undo)
9. [The purse screen in detail](#9-the-purse-screen-in-detail)
10. [Party settings](#10-party-settings)
11. [Customize](#11-customize)
12. [Good to know](#12-good-to-know)
13. [Put it online with GitHub Pages](#13-put-it-online-with-github-pages)

---

# The essentials

## 1. Getting started

Open LootPal and you get an example table: **Player 1**, **Player 2**, **Player 3** and the **Game Master**. Each player starts with 18 gold, 12 silver and 80 copper, plus a random gem worth 30 gold. The coins are round, struck with a star and ringed with beads.

1. Tap a name in the row at the top to pick whose purse you are looking at.
2. Tap the coins to count an amount.
3. Slide the big gold knob all the way to the right to pay.

To rename someone, tap their name on the purse and type. Add or remove players under the **Party** tab at the bottom.

## 2. Paying and receiving

Choose **Pay** or **Pocket** next to the character's name.

- **Tap** a coin to add one. Tap **+50** under a coin to add fifty at once (the step can be changed or switched off in Customize). **✕** clears the amount.
- **Slide** to confirm. Nothing happens until you slide all the way.
- **Change is automatic.** Pay 3 copper with only silver in the purse, and LootPal breaks a silver coin and gives you the change. The line under the amount tells you before you slide.
- When paying, you can't count more than the purse holds. Receiving has no limit.

Players pay an NPC by default. To pay another player instead, tap the *To NPC* line below the coins (see [The receipt](#5-the-receipt-who-and-what-for)).

**Made a mistake?** Tap **Undo** in the message after each transaction (it stays for six seconds), or tap the small red **×** at the end of the entry in the Ledger later. Undo still works after the page reloads.

## 3. The Game Master

Tap **Game Master** in the character row. The GM's coffers are **unlimited**, so coins go straight to the players.

- **Give or Take.** The switch at the top. *Give* hands out treasure and rewards. *Take* collects fines, taxes or tolls, and LootPal checks that everyone can pay.
- **Who gets it.** The tags under the coins. **All players** is the default and shares the amount between all players (not the party purse). Tap a single player to give only to them.
- Count the amount and slide, as with a player.

More GM tools (Split or Each, Mixed bag, the GM's book) are described in [More for the Game Master](#more-for-the-game-master).

## 4. Save your table

LootPal saves itself in the browser it runs in, but browsers can forget, for example when you clear your history. **Make a backup after each session** under the **Table** tab:

- **Name of the NPC tag.** Change "NPC" to something that fits your world, for example *The Realm* or *Merchants*.
- **Table name.** Give the table a name, for example *Curse of the Crimson Crown*. It's used in the save file's name and shown when you load a code or file, so you know which campaign it is.
- **Last backup.** The tab shows when the last backup was made and how many payments happened since. A small gold dot on the Table tab means there are payments that aren't backed up yet.
- **Save code.** A line of letters and numbers holding the whole table. Copy it into a note or a message to yourself.
- **Save file.** Downloads the table as a small `.json` file.
- **Load.** Paste a code or pick a file. LootPal shows what it holds and asks before replacing the current table.

Save codes and files also move a table to another phone or browser.

**Start a new table.** At the bottom of **Table**: wipes the table and starts fresh with Player 1–3, the standard coins, an empty ledger and no deeds earned. The first tap lists everything that will be deleted; tap again to go ahead. Undo can't bring it back. Make a save code first if you might want the old table back.

---

# More detail

## 5. The receipt: who and what for

The **Receipt** tick box sits at the end of the tags below the coins, after the players. It has a dashed outline, since it isn't someone to pay. Tick it to open the receipt, untick it to close it. For players, open the *To* line first; when receiving, it's on its own. On the narrowest phones it shows just the box. It opens the receipt. Everything in it is optional and goes into the ledger.

**Who gets it (players).** Below the coins, a line shows who a payment goes to: *To NPC* by default. Tap it to open the tags, the same place the GM picks players.

- Tap another player to pay a companion, and the coins go straight into their purse.
- To pay several companions, tap **Everyone else**, or hold a name to add or remove players. Then choose **Split** (the amount is shared, what doesn't divide evenly stays in your purse) or **Each** (every one of them gets the full amount). Only players can be picked together, not the GM or the party purse.
- **Mixed bag** (shown once you pick a companion) pays with a random mix of your own coins worth exactly the amount, without change, when such a mix exists.

The line folds away again after each payment and goes back to NPC (unless the receipt is open, see below).

**When a player pays an NPC,** the receipt has **To** (for example *the blacksmith*) and **For** (for example *a longsword*).

**When a player receives:** **From** (for example *the innkeeper* or *a chest*) and **For**.

**When the GM gives:** **Source** (in the story, for example *a noble knight*) and **What** (for example *crypt treasure*). When taking, the field is **Reason** (for example *a fine for brawling*).

**Where** (everyone): the place it happened, for example *Saltmarsh*. The ledger shows it at the end of the line, after a pin: *Player 1 to Merchant for Gear 📍 Tavern*.

Under *Where*, the places you've used recently show as tags: one tap fills one in, tap again to clear it. Receipts can be switched off under **Customize → Receipt**.

The receipt starts empty for every payment, and again when you switch to another character or between Pay and Pocket (or Give and Take). Once ticked, it stays open for the next payments until you untick it; each device remembers. Unticking clears what you typed, so an unticked receipt never ends up in the ledger.

The ledger then reads like a sentence: *Player 1 to the blacksmith for a longsword*.

For players, folding the *To* line hides the receipt but keeps it: the line then shows it, e.g. *To the blacksmith · for a longsword*.

### More for the Game Master

- **Several players.** Hold a name in the tags to add or remove more players.
- **Split or Each.** A switch next to Mixed bag. With several players chosen, *Split* divides the amount between them and *Each* gives the full amount to every one of them. What doesn't divide evenly stays in the coffers.
- **Mixed bag.** On Give, pays treasure out as a random mix of coin types with exactly the same value, like a real hoard. On Take, takes a random mix of the coins each player holds, without change (or with change if no exact mix is possible). Off by default.
- **The Game Master's book.** Shown under the GM's purse and in the ledger. Tap its title to fold it away; each device remembers. It shows how much the players paid in, how much the GM paid out, and every player's current purse.

## 6. The party purse

A shared purse for the group. Add it under **Party → + Add a party purse**.

- Players pay into it like paying a companion.
- It gets no share of "All players" payouts from the GM, and no starting purse.
- **To share it out**, tap the *To* line below the coins on the party purse and pick **Split in party**. With no amount counted, it fills in everything in the purse. Tap coins down to share less. What doesn't divide evenly stays in the purse.
- It can also pay an NPC, like a player.

## 7. The gem bag

Gems are treasure too. Below the purse card sits the **Inventory** menu, a stitched leather bar showing what the card holds right now (*Inventory · Coins*). It starts open, with one row of tiles: **Coins**, **Gems** and two smaller locked tiles for things still to come (equipment or a map scroll case, for example). Tap **Gems** and the gem bag takes the place of the coins (the menu stays open, so going back is one tap; tap the bar to fold it, and your phone remembers that); everything else works the same: **Pay | Pocket** (GM: **Give | Take**), the *To* line, the receipt and the slide.

Gems live in **pouches**. Every pouch is a 4 × 3 grid on a dark tray; each gem lies on a soft plate the size of its footprint, with its worth below it in coin colours. When a gem doesn't fit, a **new pouch** opens by itself (*Pouch 2* …, up to six), and an empty extra pouch goes away again. Tabs above the tray show each pouch with what it holds (*Pouch · 57g*); tap a tab to open it, tap ✎ on the open one to rename it, or drag a gem onto a tab to move it there. The party purse has pouches too.

Sizes are picked as the cells a gem takes in the pouch: **1×1, 1×2, 2×2, 1×3, 2×3 or 3×3**, each tile drawn as its cells. Gems that aren't square can lie across.

16 cuts, in any size: round, oval, cushion, princess, diamond, emerald cut, Asscher, baguette, then (under *More cuts*) pear, heart, trillion, hexagon, octagon, egg, crystal and rough stone. A cut stretches along a long size (a round becomes a long oval stone), but is never squashed. Heart, trillion and Asscher keep their shape, so they come only in square sizes.

**Pocket** a gem (the GM: **Give**): the card turns into a quick screen. The gem shows big at the top, its name below it (filled in for you; tap to rename), then its **worth**, big and in coin colours. Set the worth with the slider, which snaps to round sums from 1 to 1,000 gold (all the way left means **?**, not appraised yet); tap the number to type it; or open **Fine-tune** to count it with the coin cards, for odd values like 12g 5s. Two big buttons follow: **🎲 Roll a gem** makes a random one (mostly 1×1, now and then 1×2, rarely bigger, a 3×3 about once in 200; round, oval, cushion and emerald cuts most often, hearts and trillions seldom), and **✎ Customize** slides up a sheet (tap the name or worth in its preview bar to change them) with size, cut, colour, eight styles (faceted, cabochon, banded, two-tone, opalescent, clouded, speckled, cracked) and two sliders side by side (shade, and scale set a little apart), its own preview on top with the dice and start-over signs, and **Done** at the bottom. Below sits the **From** line (where the gem came from, like *To* when paying), then the slide. Tapping the big gem jumps to its worth. **Not appraised yet?** Leave the worth empty: the gem shows **?** in the pouch, counts as nothing towards wealth, and gets its worth later (tap it, then Edit or the big gem). Selling a **?** gem asks what the merchant offers. Beside it sit small signs, like the ones around the coin number: the dice (top left) rolls a new gem, the arrow below it goes **back** one step (the previous roll, cut, colour or worth), and the sliders (top right) open the Customize sheet. Pocket always opens with a freshly rolled gem, ready to slide or change.

**Pay** with a gem: tap it in the bag and it's on the table. Then, like coins:

- **To NPC** (the default) sells it: a merchant pays its worth minus their cut (40% by default, set in Customize). After haggling, or with a fence, tap **✎** beside the price: the receipt opens at **Merchant's cut**, where − and + change the cut for this sale in 5% steps, and its tick box switches the cut off (the merchant pays the full worth). For a gem whose worth is still **?**, ✎ asks what the merchant offers instead. The slide says *Sell for …*, and the ledger keeps both: *Sold … Large ruby · worth 50g · +35g*.
- **To a companion or the party purse** gives it. The gem flies over.
- **Lost**, the last tag after the players: the gem is gone for good (dropped, stolen, crushed). It goes in the ledger as *Lost*.

**The GM** gives new gems as loot (**Give**: pick one player or the party purse, make the gem, slide) or takes one (**Take**: pick a player, tap one of their gems, slide).

**Arrange a pouch.** Drag a gem to move it: the cells light up green when it fits, red when it doesn't. Drop it on a gem of the same size to swap them. **Double-tap** a long or special gem to turn it (or the turn sign at the left, below Sort, or the R key). **Sort** (the small sign at the top left) packs the open pouch tight, biggest and most valuable first. **Edit** (the sliders sign at the top right, where the coin sign sits in coin view) opens the Customize sheet for the selected gem, with Cancel and Save; tapping the big gem opens it with the worth ready to type.

**Full pouches.** Only when all six pouches are full is there no more room.

**Wealth and ledger.** Gems count towards wealth and the wealth title. Gems share the coins' ledger and are written the same way: who, to or from whom (from the receipt), what for, then the gem in its colour, e.g. *Sold · Player 1 to Gimble for rent · ◆ Large ruby · 40% merchant's cut · +24g*. The amount is the gem's worth (or the coins a sale brought in), plus when it comes in and minus when it goes out. Gem lines count in the day totals, show in Export, and can be undone like a payment.

## 8. Ledger and undo

The **Ledger** tab (first of the tabs at the bottom: Ledger, Party, Customize, Table) shows who paid whom, what for, and how much. It shows the newest 50 entries, grouped under their headings; **Show 50 more** goes further back. Tap the **Entries** heading to fold the whole list away and get straight to the deeds and your book; each device remembers. The ledger keeps the last 2,000 payments; Export or a save file is the archive beyond that. Rename a character and their old entries follow.

**Days and places.** Every payment is stamped with its date, and the ledger groups entries by game night (anything before 6 am counts as the night before), each heading with what came into the party (green) and went out (red). Payments between players don't count, since the money stays in the party. The GM can name a game night: tap its heading (✎), type a name such as *The heist at Saltmarsh*, and press Enter. The date stays beside it, and Export uses the name too. The receipt has a **Where** line: type a place, for example *Saltmarsh*, or tap one of the tags, and the place shows at the end of that payment's line. Like the other fields, it is empty again for the next payment.

**Everyone or one character.** The switch at the top (*Everyone* or *Only Player 1*) shows either all entries or only those involving the character you're looking at. The day totals then show what came in and went out for that character.

**Export.** Shows the whole ledger as plain text, grouped by day, with each payment's place, for campaign notes or a recap. **Copy** puts it on the clipboard, **Save as a file** downloads it as a .txt file.

**Undo.** Right after a payment, the message has **Undo** for six seconds. Later, use the small red **×** at the end of an entry in the ledger (tap twice: the first tap asks *Undo?*): a player can take back their own newest payment, the GM any of the last ten. Only that one payment is undone; everything paid after it stays. If the coins have already been spent (for example a gift the receiver used straight away), undo is refused. Deeds earned by that payment are taken back too.

**Your own book.** Below the entries, a folded line "Player 1's book". Open it for a little lifetime summary in one sentence, for example: *Player 1 has earned 12g 4s and spent 8g 3s. Biggest purchase: a longsword, 1g.* It also names the biggest haul (the largest single sum received). Gifts to and from companions are mentioned when there are any. The Game Master's book stays on the GM's purse and isn't shown in the Ledger.

**Deeds.** When deeds are on, each character's deeds are shown in the ledger, below the entries. Tap the heading to fold them away; each device remembers. Tap an earned deed to hear its tune.

## 9. The purse screen in detail

**Faster counting**

- **Hold** a coin to count up, faster and faster.
- **Drag** up or down on a coin to wind the amount.
- **Tap the number**, or the small keyboard sign on the left, to type the amount. Handy for big treasure. Tap it again to close the fields.
- **↻ Same as last time.** Below the keyboard sign. Each character remembers their last payment: the amount, who got it, Split or Each, Mixed bag and the receipt (To, For, Where). One tap fills it all in again, for example the inn for another night; then slide as usual. It shows only while nothing is counted, and only in the same mode (Pay or Pocket, Give or Take).
- **Edit coins.** The small coin sign at the top right, level with the keyboard sign, opens the **coin sheet**: one tab per coin (plus **+** for a new one), the chosen coin big in a sticky top with its name, short name and worth (🎲 rolls a new look, ↶ goes back a step), then its shape, colour and face as cards, its finish (rim, surface, thickness), Shade and Scale sliders, and its weight. Remove a coin or reset to Gold, Silver & Copper at the bottom (tap twice). Changes apply to everyone at the table.
- **Swipe** across the Pay | Pocket switch (or the GM's Give | Take), or sideways across the amount, to change sides.

**Clear.** The ✕ on the right, below the coin sign, clears the amount. It only shows while something is counted.

**Stacks.** Every coin in the purse is drawn, ten to a stack. Every full fifty goes into a small pouch with a count, so 137 silver shows two pouches (×2) and 37 loose coins. The pouch is stamped *50*, so it's clear what it holds.

**Quick add.** Under each coin's name, a small **+50** adds fifty of that coin at once; hold it to keep adding. When paying it's dimmed if you can't afford that many more. Under **Customize → Coins**, switch **Quick add button** off, or choose +10, +50 (the default) or +100. While you count an amount, coins that will leave fade out, change you get back shows as dashed coins, and the number below shows the change, for example **10 → 9**.

**Coloured amounts.** Amounts in text, such as the ledger, show each coin in its own colour, so *6g 2s 15c* is easy to read at a glance.

**Title.** The small label under the name is the wealth title, for example *Comfortable*.

**Status.** Under the leather card, each character has a small status card with tiles: **Wealth** (total worth as small coins, plus the wealth title) and, if purse weight is switched on, **Weight** (the weight, a description like *Tugs at your belt* and a belt bar that fills from green to red). Tap the card's headline to fold it away; folded, it still shows the total worth. The GM has the Game Master's book here instead.

## 10. Party settings

Under the **Party** tab:

- **Who's at the table.** Rename or remove players. Tap a character's round picture to give them an icon (warrior, wizard, thief, sword, dragon…) and a colour; the letter stays the default. The Game Master starts in violet (the NPC tag always takes the GM's colour) and the party purse in teal, so they stand apart from the players; a thin line separates each of them in the character row. Leave the name empty when adding to get *Player 4*, *Player 5* and so on. Removing asks twice.
- **+ Add a party purse.** See [The party purse](#6-the-party-purse).
- **Starting purse.** What new players start with. Set everything to 0 for empty purses. **Give everyone the starting purse** sets every player's purse to it (asks twice, and can be undone). Below it, **Starting gem worth** (in the top coin): every new player also gets a random gem of that worth, of a size that suits it. 0 means no gem. *Give everyone the starting purse* only sets the coins; gems already in a pouch stay.

## 11. Customize

Under the **Customize** tab, or the **Customize** button in the top bar (next to *Sound on*):

**Coins.** *Edit coins* opens the coin sheet (the same as the coin sign on the purse); quick add and purse weight stay here. Up to six coin types. For each coin: name, short name (used in amounts like *6g 2s*), shape (round, holed, square, triangle, hexagon, diamond, or the historical hammered, clipped, cob, square-hole, octagon and cut-half), finish (a plain, lined, beaded or lettered rim; a glossy, satin or worn surface; thin, normal or thick), colour (16 metals and stones, from gold, brass and electrum to mithril and obsidian, each a shade darker or lighter if you like), face (its letters, a number, or one of 18 heraldic motifs struck into the metal, like a crown, king, lion, castle, rose, orc, dwarf or elf), size on the coin card and worth. The cheapest coin is the base and is always worth 1. Enter every other coin's worth in any cheaper coin, for example a platinum worth *20 Gold* (the base coin is the default). It has to come out as a whole number of base coins, so uneven systems like 12 pence to the shilling work too. The worth is kept in base coins, so if you later change gold's worth, the platinum keeps its value in copper. Removing a coin (tap × twice), or resetting to gold, silver and copper, changes everyone's coins at their value, so nobody gets richer or poorer.

**Purse weight** (on by default, under Coins). Weight, description and belt bar. Set grams or ounces per coin and when the belt is full.

**Wealth.** The wealth title (on by default): a ladder of titles from *Penniless* to *Filthy rich*. Rename the steps and set the amounts to fit your campaign.

**Gem bag** (on by default). Switch the gem bag off, and choose the merchant's cut when selling (5–100% in 5% steps, 40% by default).

**Receipt** (on by default). Switch off to remove the Receipt tick box entirely; payments then go in the ledger with just the amount. One setting for the whole table.

**Deeds** (on by default). Six small achievements per character, such as *First Purchase* or *Dragon's Hoard*, each with its own lute tune.

**Language.** English or German. See [Good to know](#12-good-to-know).

**Sound settings.** Volume, and each sound on or off: counting coins (metal on metal), paying and receiving (coins on a wooden table and a leather pouch), deed tunes, a flourish for GM payouts, and vibration on phones that support it. The **Sound on** button at the top switches all sound at once.

## 12. Good to know

- **One table per device.** Each phone or browser keeps its own table. Syncing between phones is planned, but not there yet. Until then, move tables with a save code or file.
- **Languages.** LootPal speaks English and German. It picks the language of the phone or browser, and you can switch under **Customize → Language**. The choice is kept per device, so a German player and an English GM can share a save code. Names LootPal gave, like *Player 1* or *Gold*, change with the language. Names you chose stay as they are.
- **On your home screen.** Open LootPal in the browser and choose **Add to Home Screen** (iPhone: the share button in Safari; Android: the ⋮ menu in Chrome). It gets the LootPal icon and opens full screen like an app. On iPhone, the home-screen app keeps its own table, separate from Safari, so move an existing table over with a save code.
- **Your data stays with you.** Nothing is sent anywhere. The only thing loaded from the internet is the font.
- **Online and claude.ai versions are separate.** Tables don't carry over between them, except through a save code or file.
- **Shorter save codes.** Untick *Include the ledger* when making a save code.
- **Older saves.** Save codes and files from earlier versions still load.

## 13. Put it online with GitHub Pages

1. Create a new repository on GitHub, for example `lootpal`.
2. Click **Add file → Upload files** and upload all the files: `index.html`, `manifest.webmanifest`, the icons (`apple-touch-icon.png`, `favicon.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`), `lootpal-logo.png`, this README and the CHANGELOG. Commit.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick the `main` branch and the `/ (root)` folder, then **Save**.
5. After a minute or two, LootPal is live at `https://<your-username>.github.io/lootpal/`.

To update it later, upload a new `index.html` over the old one. You can also open `index.html` straight from your computer by double-clicking it.
