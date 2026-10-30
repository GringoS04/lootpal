# Changelog, full history

Every upload of LootPal, step by step, newest first. The short version is in [CHANGELOG.md](CHANGELOG.md).

LootPal is in **early alpha**. The middle number marks milestones (for example sync between phones, or equipment). The last number counts uploads within a milestone. 1.0 is the full companion, tested at the table.

---

## 0.3.45 · 2026-10-30

### Added
- **Two new gem styles**:
  - **Opalescent**: soft patches of rainbow fire across the stone, like opal or labradorite;
  - **Clouded**: milky, with soft wisps inside and a pale blue sheen, like moonstone.

### Changed
- **The style cards** in the Customize sheet now run: Faceted, Cabochon, Banded, Two-tone / Opalescent, Clouded, Speckled, Cracked.
- **Star and Runed** can't be picked any more. Gems that already have them keep their look; when you edit one, its style shows as an extra card at the end.
- **The gem generator**: Faceted is still the most common, then Cabochon, Banded and Two-tone; Clouded and Speckled now and then; Cracked and Opalescent are the rare ones.

---

## 0.3.44 · 2026-10-30

### Changed
- **A new table's coins** (and *Reset to Gold, Silver & Copper*): round, struck with a **star**, a **beaded** rim, glossy, normal thickness, full size. Colours and shade as before.
- **A new table's starting purse**: **18 gold, 12 silver, 80 copper** (was 5, 10 and 25).

### Added
- **Starting gem.** On a new table every player also starts with a **random gem worth 30 gold**, of a size that suits its worth. In Customize → Party, below the starting purse, **Starting gem worth** sets it for new players (in the top coin; 0 for no gem). It's hidden while gems are off. *Give everyone the starting purse* still only sets the coins, so nobody loses a gem.
- Tables you already play keep their coins and purses; their starting gem is 0 until you set one.
- **Star** moves into the first eight faces (as a new table's face); Castle goes behind *More faces*.

---

## 0.3.43 · 2026-10-30

### Fixed
- **Eight shapes before More shapes**: a coin with one of the extra shapes (Triangle, Hexagon, Diamond, Cut half) added it as a ninth card while the list was folded. Folded now always means eight; the list still opens by itself when the sheet opens on such a coin.

---

## 0.3.42 · 2026-10-30

### Changed
- **Inventory menu**:
  - starts **open**, and **stays open** after you pick Coins or Gems, so switching back and forth is one tap;
  - the tiles are one compact row, lower than before; the chosen one is lit, and the two locked *Soon* tiles are narrower and dimmer;
  - folding it (tap the header) is remembered on this phone or computer only, not for the whole table.

---

## 0.3.41 · 2026-10-30

### Added
- **Two more hand-made shapes**, both cousins of Hammered:
  - **Clipped**: a round coin with slivers shaved off its edge, as coin clippers did with silver;
  - **Cob**: a chunk cut from a bar and struck, all uneven corners, like Spanish pieces of eight.
- **More shapes / Fewer shapes** in the coin sheet: Round, Hammered, Clipped, Cob, Square, Octagon, Donut and Square hole show at first; Triangle, Hexagon, Diamond and Cut half wait behind the button (it opens by itself when the coin already has one of them).

### Fixed
- The **Square hole** card in the sheet showed an empty coin; it now shows the metal.
- **Cut half** coins no longer show a motif, since half of it would be gone.

---

## 0.3.40 · 2026-10-30

### Added
- **Four new coin shapes** from coin history:
  - **Hammered**: hand-struck, a little out of round, the way most medieval coins looked;
  - **Square hole**: round with a square hole, like Chinese cash coins (no motif, like the donut);
  - **Octagon**: eight sides;
  - **Cut half**: a coin cut in two to make change, the motif cut with it.
- **Finish**, a new section in the coin sheet, set for each coin:
  - **Rim**: *Plain*, *Line* (a raised ring), *Beads* (the dotted border of medieval coins) or *Legend* (the coin's name struck around the edge, like *✠ GOLD ✠ GOLD*; small coins show a line instead);
  - **Surface**: *Glossy*, *Satin* (a soft metallic sheen) or *Worn* (grain, fine scratches and a darker rim);
  - **Thickness**: *Thin*, *Normal* or *Thick*, how tall the coin stands.
  - New coins and existing ones start plain, glossy and normal, so nothing changes until you pick something. 🎲 rolls the finish too, and ↶ Back takes it back.

### Changed
- **Coins are drawn as one picture**: the edge and rim follow each shape, so hexagons, triangles, diamonds and the new shapes get a proper edge too.

---

## 0.3.39 · 2026-10-30

### Changed
- **Struck coin faces.** The motif is no longer printed flat on the coin: it stands up out of the metal, in the coin's own colour, with a light edge at the top left and a shadow at the bottom right. Letters and numbers too. Small coins in lists keep a darker motif so it still reads.
- **The faces, redrawn** as bold heraldic shapes, 20 in all:
  - shown: Letters, Number, Crown, **King** (a crowned head, front on), **Cross** (a long cross with pellets), Lion (now rampant), Eagle, **Castle** (three towers);
  - behind **More faces**: Shield (with a bend), Sun (with a face and straight and wavy rays), Crescent, Star (six points), Fleur-de-lis, **Rose**, **Keys** (crossed), Dragon, Skull, **Orc**, **Dwarf**, **Elf**.
  - Heads, Tails, Tower and Key become King, Cross, Castle and Keys on existing coins. Coins with a face that was dropped (crossed swords, anchor, ship, tree, wheat, anvil, double axe) keep it.
  - The new faces can also be a character's picture.
- **Metals.** Four new ones: **Brass** (dull, slightly green yellow), **Electrum** (pale green-gold), **Rose gold** and **Mithril** (pale blue). **Silver** is now a neutral grey-white, **Platinum** a cooler blue-violet and **Bone white** a warm cream, so the pale ones no longer look alike. The swatches are ordered by neighbouring colours.
- **Coin sheet**:
  - the coin, its name, short name and worth sit in a **sticky top** that stays while you scroll, with **🎲** (a new look: metal, shape, face, shade and scale, never the name or worth) and **↶ Back** (undoes the last change to a coin's look, step by step);
  - **shape** comes before **colour**, like cut and colour for gems;
  - **More faces / Fewer faces** folds the second set of faces;
  - **Shade** (darker or lighter metal) and **Scale** (the coin's size on its card and in its stacks), side by side as for gems, shown live while sliding;
  - **Weight** has its own heading, with *g* or *oz* inside the field.

### Fixed
- On phones, the small coin stacks of the pay screen showed through the coin sheet. They now stay underneath every sheet.

---

## 0.3.38 · 2026-10-29

### Changed
- **Coins are edited in a sheet**, in the same style as gems. The coin sign on the purse (and *Edit coins* in Customize → Coins) slides it up:
  - **one tab per coin** (Gold · Silver · Copper) and **+** for a new one;
  - the chosen coin **big on top**, with its **name** (✎), **short name** and **worth** (still countable in any cheaper coin);
  - **colour** as swatches, **shape** and **face** as cards with a live preview of the coin, the **number** when the face is a number, and the **weight** when purse weight is on;
  - **Remove** the coin and **Reset to Gold, Silver & Copper** at the bottom, both with a second tap;
  - a note that changes apply to everyone at the table, and **Done** (or tapping outside, or Esc).
- **Customize → Coins** keeps quick add and purse weight; the long list of coin fields is gone.
- Leftover translations from the old bag size and coin list are removed.

---

## 0.3.37 · 2026-10-29

### Changed
- **Pocket opens with a freshly rolled gem** (the GM's Give too): ready to slide, or change. After pocketing, the next one is rolled.
- **↶ Back** replaces *Start over*: it takes back the last change to the gem (a roll, a size or cut, a colour, a style, the shade, scale, name or worth), step by step. Beside the gem and in the Customize sheet; dimmed when there's nothing to go back to. While editing a gem it works on that gem.

---

## 0.3.36 · 2026-10-29

### Changed
- **Name and worth in the sheet's preview bar**: tap the name or the worth beside the preview (each with a small ✎) and type right there; Enter or tapping elsewhere saves. The separate Name and Worth fields and the second worth slider in the sheet are gone.

---

## 0.3.35 · 2026-10-29

### Added
- **Name and worth in the Customize sheet**, at the top: the same name and worth as on the quick screen, with a worth field and slider, so everything about a gem can be set in one place.
- The **worth slider starts at ?**: all the way left means the gem isn't appraised yet.
- Choosing a **?** gem, the line under it says *"worth unknown, tap the gem to set it"*.

---

## 0.3.34 · 2026-10-29

### Added
- **What the merchant offers.** When selling a gem, a **✎** sits beside *"a merchant pays 40g"*: tap it and type what this merchant actually offers (after haggling, from a fence …). The table's cut stays the starting point. The slide follows the new price.
- **Worth unknown.** Pocket a gem without a worth and it shows **?** in its pouch until someone appraises it; set the worth later via Edit or by tapping the big gem. Unknown gems count as nothing towards wealth. Selling one asks *"What does the merchant offer?"* first.

### Changed
- Sales in the ledger show the gem's worth beside it and the price as the amount: *Sold · Player 1 to NPC · ◆ Large ruby · worth 50g · +35g*. A gem of unknown worth shows **?** as its amount.

---

## 0.3.33 · 2026-10-29

### Changed
- **Pouches instead of one bag.** Every pouch is **4 × 3**. When a gem doesn't fit, a **new pouch** opens by itself (*"A new pouch: Pouch 2"*), up to six per character; an empty extra pouch goes away again. The party purse works the same way. Bags from earlier versions are packed into pouches once.
- **Tabs above the bag** show each pouch with its total worth (*Pouch · 91g*). Tap a tab to open that pouch, tap **✎** on the open one to rename it, **drag a gem onto a tab** to move it there. The GM sees a player's pouches the same way when taking.
- **One dark tray** with faint lines between the slots; every gem lies on a **soft plate** the size of its footprint, so the lines disappear beneath it.
- **The worth is easy to read**: a price label at the bottom centre of each plate, larger and in coin colours.
- **Smaller slots** (at most 64 px), so the slide stays in view on small phones, as with coins.
- **Sort** is a small sign at the top right of the amount area. The hint moved into the line under it (*Tap a gem · drag to move it*, and *double-tap to turn* for a long gem).
- Long cuts sit plumper in a classic slot, so an oval no longer shrinks to a stick.
- The character's name has a small **✎** beside it, like every other name you can change (hidden on very narrow phones).

### Removed
- **Bag size** in Customize → Gem bag (every pouch is 4 × 3).

---

## 0.3.32 · 2026-10-27

### Changed
- Cleanup after the gem rework: styles left over from the old one-page gem maker (the dashed random button, the old preview row and the worth field with its coin list) and three unused translations (*Small*, *Random gem*, *Editing …*) are gone. The slider styles are merged and the style sheet's section notes are up to date. No visible changes.

---

## 0.3.31 · 2026-10-27

### Removed
- The **Glow** and **Clarity** sliders, and with them the aura and milky looks. Shade and Scale now sit side by side. Gems made with glow or clarity simply look as they would without.

---

## 0.3.30 · 2026-10-27

### Added
- **Eight gem styles**: Faceted, Cabochon, Speckled, Cracked, and new **Star** (a six-ray star of light, like a star sapphire), **Banded** (soft stripes, like agate), **Two-tone** (blending into a second colour, like ametrine) and **Runed** (a small glowing rune: an enchanted stone).
- **Glow** slider: from none to bright, a soft aura in the gem's own colour that spills a little over its cells.
- **Clarity** slider: from clear (see-through) to milky and opaque.
- The sliders sit two by two: Shade and Glow, Clarity and, set apart by a thin line, Scale. All cards and the preview follow as you slide.
- **Random gems**: faceted most often, star and runed rarely; now and then a gem glows or is milky, and a runed stone always glows.

---

## 0.3.29 · 2026-10-27

### Added
- The dice and start-over signs also sit in the Customize sheet, beside its preview.

---

## 0.3.28 · 2026-10-27

### Added
- **Two small signs beside the gem** when pocketing (the GM: giving), in the same style as the signs around the coin number: a **dice** on the left rolls a new gem, a **round arrow** on the right starts over with a plain one (round ruby, no worth, no name). While editing, the arrow goes back to the saved gem and the dice is hidden.

---

## 0.3.27 · 2026-10-27

### Changed
- **Size and cut are separate choices.** Pick a size (Classic, Long, Large, Extra), then any of **16 cuts**: round, oval, cushion, princess, **diamond** (new), emerald cut, Asscher, baguette, and under **More cuts ▾** pear, heart, trillion, hexagon, octagon, egg, crystal, rough stone.
- A cut **stretches along a long size** (a round becomes a long oval stone, a crystal fills a 1 × 3) and is never squashed; outlines stay the same thickness. Heart, trillion and Asscher keep their proportions, so they are offered only in square sizes and dimmed in the others.
- **Extra** offers a footprint: **2 × 3**, **1 × 3** or **3 × 3**. Every non-square gem can be turned.
- Random gems pick from all cuts that fit the size; Extra comes mostly as 2 × 3.
- Gems from earlier versions keep their look; editing one shows its old cut until you pick a new one.

---

## 0.3.26 · 2026-10-26

### Changed
- **Pocketing a gem (and the GM giving one) is a quick screen**, mobile first: the gem a little bigger at the top, its **name** right below it (filled in, tap to rename), then the **worth**, big and in coin colours like the coin number.
- **Worth slider** in gold that snaps to round sums (1, 2, 3, 5, 8, 10, 15, 20 … 500, 750, 1,000). Tap the number to type any amount. **Fine-tune** opens the coin cards below it for odd values (12g 5s): tap or drag them like a payment.
- **Two big buttons**, side by side: **🎲 Roll a gem** (the dice tumbles) and **✎ Customize**.
- **Customize slides up as a sheet** with its own preview pinned on top: size as a switch (**Classic** · Long · Large · Extra; *Small* is now *Classic*), cut, colour, style, then Shade and, a little apart, Scale. **Done** (or tapping outside, or Esc) slides it away. The slide and the To line never move.
- **From line** when pocketing a gem, mirroring the To line when paying: it shows where the gem came from and opens the receipt.
- **Edit** uses the same quick screen with Save and Cancel; the bag steps aside while you edit.
- **Random gems**: 75% classic, 20% long, 3% large, 2% Extra (worth 60–200).

---

## 0.3.25 · 2026-10-25

### Fixed
- The cushion cut's corner lines stuck out past its rounded corners; they now start on the edge (also on the large cushion).

---

## 0.3.24 · 2026-10-25

### Changed
- **Small rough stone** replaces the donut, so the rough stone now comes in every size: small (1 × 1), large (2 × 2) and Extra (3 × 2). Donuts already in a bag keep their shape.

---

## 0.3.23 · 2026-10-25

### Changed
- **Large rough stone** replaces the large hexagon among the large cuts: the uneven Extra stone, shaped to fit 2 × 2. Large hexagons already in a bag keep their shape.

---

## 0.3.22 · 2026-10-25

### Added
- **Scale** slider below Shade (German *Größe im Feld*): how much of its cells a gem fills, from 60% to full, in five steps. Only the look changes; the gem still takes the same room in the bag. The preview follows as you slide, Edit keeps it, and the random gem now and then picks a slightly smaller one.

### Fixed
- While sliding the shade, the Extra cut cards (egg, crystal …) were redrawn at the wrong size.

---

## 0.3.21 · 2026-10-25

### Added
- **Special** (German *Extra*), a fourth size beside Small, Long and Large, where each cut has its own size, shown on its card: **egg** 2 × 3 (smooth, narrower at the top, with soft bands), **large oval** 2 × 3 (faceted), **crystal** 1 × 3 (a tall six-sided prism) and **rough stone** 3 × 2 (an uneven, chunky stone). They turn like long gems (double-tap, ⟳ Turn or R). The random gem sometimes picks one, worth 40–150.

### Changed
- **Large cuts**: large stone and Asscher stay; **large cushion** and **large hexagon** (the small cuts at twice the size) replace geode and uncut crystal. Geodes and crystals already in a bag keep their shape.
- Turning works for every gem that isn't square.

---

## 0.3.20 · 2026-10-25

### Changed
- **Octagon** replaces the pearl cut, which looked almost like the round one. The small cuts now run round, octagon, hexagon, princess, then cushion, trillion, heart, donut. Pearls already in a bag keep their shape; the pearl colour stays.

---

## 0.3.19 · 2026-10-25

### Added
- **Donut**, a small ring-shaped stone, so the small cuts fill two even rows of four. Sorted with the faceted cuts first (round, princess, cushion, hexagon), then the playful and smooth ones (trillion, heart, pearl, donut).

---

## 0.3.18 · 2026-10-25

### Added
- **Four large cuts** instead of two: large stone, **Asscher** (a square step cut with stepped facets) and **geode** (a split rock with gem crystals in its hollow; the style shows inside the hollow), plus uncut crystal. A geode is named like *Amethyst geode* (*Amethystdruse*).

---

## 0.3.17 · 2026-10-25

### Removed
- The **marquise** cut is no longer offered (long gems: emerald cut, baguette, oval, pear). Marquise gems already in a bag keep their shape, and editing one still shows it.

---

## 0.3.16 · 2026-10-25

### Changed
- **Big preview above the slide**: the gem preview at the end of the maker takes half the width, with the gem's **name and worth** beside it, and the Shade slider below them at half the width. Everything updates as you type, pick or slide, so you check the gem right before sliding it into the bag.

---

## 0.3.15 · 2026-10-25

### Changed
- **Pocket shows only the gem maker**: the bag grid steps aside, the gem sits big at the top, then the maker. The bag comes back once the gem is in.
- **Smaller bag by default: 3 × 4**, and **3 × 3** is possible too (Customize → Gem bag). Tables whose gems need more room stay at 4 × 4.
- **Lose** is no longer a button. Losing a gem works like paying: choose **Lost**, the last tag after the players, and slide (*Slide to lose it*). The ledger line reads *Lost · Player 1 · ◆ Ruby · −5g*, with a receipt if you like.

### Added
- **🎲 Random gem** at the top of the maker: a random size, cut, colour, style, shade and a fitting worth (small 2–12, long 8–30, large 25–90 in the top coin). Change anything, then slide.
- **Four new cuts**: princess, hexagon and heart (small), baguette (long).

---

## 0.3.14 · 2026-10-25

### Changed
- **Receive is now Pocket** (German: *Einstecken*): what you do at the table with loot, a reward, a merchant's payment or a gem you found. The switch reads **Pay | Pocket** for coins and gems; the GM keeps Give | Take. Ledger lines (*Got*) stay as they are.
- On very narrow phones the switch's words sit a little tighter, so the character's name keeps its room.

---

## 0.3.13 · 2026-10-25

### Changed
- **The gem maker is sorted by use**: Worth first, then Name, then the look from big to small: Size, Cut, Colour, Style, Shade. Tapping the big gem lands on Worth at the top, so there's less scrolling.
- The Cut cards show the chosen style and shade too, so every card previews the gem as it will be.

### Added
- **Shade preview**: a gem card beside the Shade slider shows the gem as you slide; the Cut and Style cards and the big gem follow at once. *Darker* and *Lighter* sit under the slider.

---

## 0.3.12 · 2026-10-25

### Changed
- **Tapping the big gem** no longer opens the coin keyboard. The gem glints (with a soft clink), then:
  - receiving, the GM giving, or editing: the cursor jumps to **Worth**, ready to type;
  - paying with one of your own gems chosen: the gem opens in **Edit**, Worth ready to type;
  - the GM taking a player's gem: just a closer look, with name, style and worth below it.
- While editing, the big area shows the gem as you change it (it was empty).

---

## 0.3.11 · 2026-10-25

### Changed
- **Gem lines in the ledger use the coins' format**: the same kinds (Got, Paid/Sold, Gave, Took, Lost), *who · to or from whom · for what* from the receipt, then the gem with a small gem sign in its own colour, e.g. *Got · Player 1 from the dragon for the hoard · ◆ Large ruby · +40g*. A sale reads *Sold · Player 1 to Gimble for rent · ◆ Large ruby · 20% merchant's cut · +32g*.
- Amounts are signed and coloured like coins: plus when a gem comes in, minus when it goes out. A gem worth nothing no longer shows a grey "0c" without a sign.
- Removed the old gem-only sentences (*found*, *got … from*, *sold … to*) and their translations.

---

## 0.3.10 · 2026-10-25

### Changed
- **Condition** in the gem maker becomes **Style**, with four looks that are easy to tell apart even in a small cell: **Faceted** (cut lines and a glint, as before), **Cabochon** (smooth and domed, no facets), **Speckled** (golden and silver flecks inside the stone) and **Cracked** (thin glowing fissures, for magic stones). Each card previews the chosen cut and colour. A gem keeps its flecks and cracks the same every time it's drawn.
- Matt, Gradient and Dirty are gone. Gems made as Matt or Gradient become Cabochon, Dirty ones Faceted.

### Added
- **Shade** slider below Style, five steps from darker to lighter, for every colour and style. The big preview follows while you drag.

---

## 0.3.9 · 2026-10-25

### Changed
- **Ten gem colours** with more variety, in rainbow order: ruby, **amber** (new, deep orange), topaz (now a clear golden yellow), emerald, **aquamarine** (new, sea blue), sapphire, amethyst, diamond, onyx, pearl. Opal is gone from the choice since it looked almost like diamond; gems already made as opal keep their name and pale look.

---

## 0.3.8 · 2026-10-25

### Added
- **Condition** in the gem maker, below Colour: **Shiny** (facets and a glint, as before), **Matt** (flat colour, faint facets), **Gradient** (smooth colour, no facets) or **Dirty** (dulled colour with grime spots). Each card previews the chosen cut and colour in that condition. The condition shows in the bag, the amount area and when a gem flies, and can be changed with Edit. It doesn't change the gem's worth.

---

## 0.3.7 · 2026-10-25

### Changed
- Cleanup after the first gem bag: leftovers from the separate wine-red gem section (styles for the old preview, tags and selection line) and 15 unused translations are gone, among them the old gem buttons (*Give to*, *Sell for*, *Put in the bag*, *+ Add a gem*), *Save & load* and *Back*.
- The gem styles are sorted into Inventory menu, bag, amount area, tools and maker; the code's table of contents names the Inventory section.
- **Customize → Gem bag** now says the gems are in the Inventory menu.
- No visible changes otherwise.

---

## 0.3.6 · 2026-10-25

### Changed
- The **Coins | Gems** tab on the purse card's top edge is replaced by the **Inventory** menu below the purse card, above the status card: a stitched leather bar (*Inventory · Coins*) that opens a row of four square tiles, **Coins**, **Gems** and two locked tiles (*Soon*) for things to come. The chosen tile is lit, and the menu folds again after choosing. The Gems tile shows how many gems the character has. Hidden when the gem bag is switched off.

---

## 0.3.5 · 2026-10-25

### Changed
- The gem bag looks like the coins: it always uses the card's full width (also while receiving), its cells are the same dark rounded cards with the same gap, and the gem maker's Size and Cut choices are cards on the same grid. Colours sit in one even row; labels use the coin labels' small caps.
- Sort, Edit, Turn and Lose sit on the same dark surface.

---

## 0.3.4 · 2026-10-25

### Changed
- **Gems work like coins.** A **Coins | Gems** tab on the purse card's top edge switches the card; the gem bag takes the place of the coins. Pay | Receive (GM: Give | Take), the *To* line, the receipt and the slide work the same:
  - Pay: tap a gem to put it on the table. To NPC (default) sells it to a merchant, to a companion or the party purse gives it.
  - Receive: the gem maker; slide to put it in the bag.
  - GM: give new gems as loot to one player or the party purse, or take a gem from one player.
- Every gem shows its worth in its corner; the selected gem shows big in the amount area with its name and worth.
- **Double-tap** a long gem to turn it (also ⟳ Turn, or the R key).
- The separate wine-red gem section is gone.

---

## 0.3.3 · 2026-10-25

### Added
- **Drag gems** like in a PC game: the gem lifts and follows your finger, the cells it would cover light up green (fits) or red (doesn't), and dropping it on a gem of the same size swaps the two. A short tap still selects.
- **Sort** button in the gem bag: packs it tight, biggest first, most valuable first within each size.

### Changed
- The gem grid uses the bag's full width.

---

## 0.3.2 · 2026-10-25

### Changed
- Gems stand apart from the coins: in the Wealth tile on their own line, labelled *Gems*; in the folded status line after a thin divider.

---

## 0.3.1 · 2026-10-25

### Fixed
- The gems' worth in the status card (and its folded line) now looks like the coins beside it: a small gem sign and the value in the same size, instead of a large icon.

---

## 0.3.0 · 2026-10-25

### Added
- **The gem bag.** Every character has a bag below the coins, on dark wine velvet, folded by default. Gems sit on a 4 × 4 grid by size: small (1 cell: round, cushion, trillion, pearl), long (2 cells: emerald cut, oval, pear, marquise, upright or across) and large (2 × 2: large stone, uncut crystal), in nine colours.
- **Add** a gem with a live preview; the name fills itself in. **Give** it to another player, the party purse or the GM; **sell** it to a merchant for its worth minus the merchant's cut; **turn**, **edit**, **lose** or **move** it.
- The GM's bag is a workbench: make gems, then hand them out as loot.
- Gems count towards wealth and the wealth title. Found, given, sold and lost gems get ledger lines with a gem sign, count in the day totals, show up in Export, and can be undone.
- **Customize → Gem bag:** on/off, bag size (4 × 4 up to 6 × 6) and the merchant's cut (0–50%, default 20%).

---

## 0.2.101 · 2026-10-25

### Changed
- **Quick add button** is a switch in Customize → Coins; when it's on, the step (+10, +50, +100) appears below it.

---

## 0.2.100 · 2026-10-25

### Added
- **Customize → Coins → Quick add button:** Off, +10, +50 (default) or +100. One button under each coin, one setting for the whole table.

---

## 0.2.99 · 2026-10-25

### Fixed
- On short phone screens, +50 sits beside the coin's name instead of below it, so the GM's slide bar stays on screen.

---

## 0.2.98 · 2026-10-25

### Changed
- **+50 is its own small button** under each coin's name, instead of tapping the pouch. On phones the pouch sat where a thumb lands for +1, so +50 happened by accident. When paying, +50 is dimmed if you can't afford fifty more. The pouch keeps its *50* stamp and is just a picture again.

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
