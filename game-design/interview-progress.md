# Game Design Interview — Progress Notes

> **Status:** In progress. Completed Categories 1–7. Resume at **Category 8: Progression Systems**.

---

## Category 1: Vision & Concept ✓

**Pitch:** "Secret of Mana meets Stardew Valley" — or more narratively: a young farmer arrives in a town in disrepair, helps restore the land, and becomes a legendary hero.

**Inspirations & What to Borrow:**
- *Secret of Mana:* Combat style and feel, radial menus (modernized for snappy tool/weapon/magic swapping)
- *Stardew Valley:* Relationship building, town upgrades, farming and crafting systems

**Differentiator:** Narrative quality is the primary differentiator.

**Target Audience:** Players with nostalgia for 90s RPGs and modern farming sim fans.

**ESRB Rating:** Teen or lower. Not a hard design constraint — mostly means keeping gore and language minimal.

**Desired Player Feeling:** "I wish I had time for one more day." Every session should end with the player wanting to start the next cycle.

---

## Category 2: Story & Narrative ✓

**Setting:** High fantasy, whimsical medieval. Heavy magic, talking objects, magical creatures. Light tone but with genuine high stakes.

**Player Character:** Customizable appearance, defined personality/identity. Non-binary protagonist — any style of appearance, consistent character experience for all players.

**Central Conflict:** A local faction has been magically sealing off sources of water, food, and supplies to monopolize the local economy. This is wrecking the ecosystem, driving off wildlife and magical species, and financially ruining the town(s).

**Restoration Mechanic:** Restoring elemental mana seeds brings the land back. Each seed upgrades the player's tools and weapons, unlocks combat spells, causes people and magical species to return to the main town, and opens new shops and relationship options as trust grows.

**Antagonist:** The faction has a face — a specific villain who is a constant presence in the main town but not revealed as the mastermind until later in the story.

**Story vs. Gameplay Balance:** Players can ignore the main plot and focus on farming, but resource gating creates organic pull toward progression. Not forced — rewarded.

**NPC Story Arcs:** Yes — major NPCs have their own arcs that deepen as relationships grow. A few are already drafted at a high level.

**World Lore:** Narrative mentions of towns and regions beyond the playable area will be woven in to seed sequel/DLC potential.

---

## Category 3: World Design ✓

**World Structure:** One starting region that expands outward as the blight is lifted.

**Regions / Biomes:** Four confirmed, each tied to one elemental mana seed:
- Forest, Mountain, Tundra, Volcano
- A 5th or 6th region is possible but undecided.

**Towns:**
- One central hub town (starts in disrepair, grows with progress)
- Each major region has a small village with unique seeds/goods, a distinct magical race faction, and 1–2 named characters who migrate to the main town after the area is unlocked or boss defeated
- Other towns exist in lore only (referenced narratively for sequel/DLC hooks)

**Dungeons:** One major dungeon per region tied to the mana seed and area boss — mandatory story beats. Optional endgame content unlocks after the final narrative resolves. Inspired by *Secret of Mana* dungeon structure.

**World Traversal:** Seamless zone-to-zone (Stardew-style) with a broom mount for faster movement and shrines for fast travel between major areas.

**Day/Night Cycle & Dungeons:** Open design question. Leading idea: dungeons exist in a pocket dimension where time stops or slows. To be resolved.

**Exploration Rewards:** Must feel worth the effort — crafting patterns, cosmetics, meaningful lore. Minor consumables or small resource pickups are NOT acceptable as payoff for a hidden area.

---

## Category 4: Core Gameplay Loop ✓

**Day Structure:** Still being refined, but the framework is:
- Early game: crops require daily manual attention, exploration areas are nearby — tension is manageable
- Mid game: magic/sprinkler automation unlocks, enabling longer trips without crop loss
- Late game: farm runs itself, player can stay at inns/save points in distant regions overnight; tension shifts to dungeon survival

**Stamina:** Keeping a stamina-style limiting factor. Farming/gathering ingredients gains value through cooking and potion brewing that restores stamina. Open question on exact tuning vs. Stardew's model.

**Crop Decay:** Crops without irrigation will decay over time when the player is away. Sprinklers or magical equivalents prevent this. Hard blackout mechanic may be replaced by inn/rest-point choice (agency over punishment).

**Daily Activities (unlock progressively as town revitalizes):**
- Exploring — puzzle solving, combat, new areas, dungeons, mana seeds
- Farming — tilling, planting, watering, harvesting
- Socializing — conversations, cutscenes, dates, minigames
- Side games — for coin or fun
- Social events — town festivals, NPC-driven occasions
- New shops/areas as the hub grows

**"One More Day" Hooks:** Combination of:
- Crop-based (harvest ready tomorrow, weather-rare drops)
- Seasonal/time-gated (certain fish available at specific times of day or year)
- Collectibles (insects to catch)
- Social (NPC event or cutscene incoming)
- Exploration (dungeon half-cleared, area boss close)

---

## Category 5: Combat System ✓

**Feel:** Methodical, rewarding patience — weapon charge mechanic (Mana-style). Players can swing fast but are rewarded for timing and measured play.

**Weapons & Tools:**
- Yo-yo: signature combat weapon. Doubles as traversal tool (whip-like), can grab items from a distance, and gates certain items only reachable by yo-yo (e.g. items in trees). Can be imbued with elemental magic to change form/behavior.
- Axe: slow, high-damage option for players who want variety. Already present as a farming tool.
- Farming tools (watering can, hoe, etc.): not combat weapons, but have utility in combat zones — puzzle solving, uncovering buried items, activating environmental elements. Tools stay tools.

**Dodge/Parry:** Dodge only — no parry. I-frames on dodge worth experimenting with. No souls-like mechanics; accessibility and forward momentum are priorities.

**Enemy Telegraphing:** Visual wind-ups primary. Color flashes and audio cues for certain enemies or combos. Exact approach TBD per enemy type.

**Magic:** Standard MP pool governing healing, combat spells, and environmental puzzle-solving. May also have a stamina cost component — to be tested. MP as a meaningful reserve the player manages, not just a stamina extension.

**Boss Design:** Puzzle-like. Reference: Tropicalo (Secret of Mana) — clear/defeat adds in a specific order or using specific tactics before the boss becomes targetable. Elemental imbuing of yo-yo may factor into which enemies respond to which magic.

**Death:**
- Boss death: true game over, restart the day
- Overworld death: rescued by a townsperson (who rotates based on relationship level), returned home, lose a small amount of items or coin

**Difficulty Scaling:** Static — no scaling. Character level tied to activity-based skills (farming, fishing, catching, etc.). Leveling only increases HP/stamina/MP. Gear provides situational bonuses (elemental resistances, etc.) not power scaling. Players must learn encounters, not outlevel them.

---

## Category 6: Farming & Life Sim ✓

**Seasons:** Seasons affect what can be grown. Magic-based manipulation will exist but implementation is TBD. Leading options: greenhouse/enchanted plot, seed imbuing (elemental mana at a cost), or seasonal extension (soft delay, not full override).

**Soil Management:** Tilling, watering, fertilizer, harvesting. No crop rotation — too tedious. Fertilizer primarily affects growth speed. Crop quality as a mechanic is deferred — may revisit if economy needs more texture.

**Animals / Sprites:**
- Magical sprites rather than traditional farm animals, tied directly to mana seed restoration
- Each mana seed freed releases an elemental sprite (stone, water, fire, etc.)
- Sprites are assigned to roles/buildings in the sprite city and can be managed by the player
- Sprite combinations produce advanced materials (e.g. fire + stone = bricks for higher-tier buildings)
- Combination mechanics need further workshopping

**Sprite City:**
- A physical space the player walks through, outside the main day cycle
- Visited in the morning before the day begins
- Grows visually as the player invests materials into it
- Buildings provide passive bonuses (mining speed, move speed, money earned, etc.)
- No hard locks — all buildings eventually buildable, but investment order shapes the experience
- Punishment for passing out away from farm: player misses their sprite city visit that day

**Dual Shipping Bin System:**
- First rescued sprite adds a second shipping bin to the farm
- Bin 1 → town (sells for coin)
- Bin 2 → sprite city (supplies upgrade materials)
- Creates a daily resource allocation decision: money vs. progression

**Farm Layout:**
- Fully free customization based on recipes the player has unlocked
- Expansion comes from clearing space in the world, not upgrading specific plots
- Player house is the one exception — it has tiered upgrades

**Technical Note:** Design an `Upgradeable` base class/interface now so the player house upgrade system can be reused for other world objects (shrines, outposts, sprite buildings, etc.) without retrofitting later.

---

## Category 7: NPC & Social Systems ✓

**NPC Count:** 10+ already have rough character profiles. Full roster likely 20+. Population grows as the town revitalizes — new characters migrate back as areas unlock.

**Relationship Depth:** All of the above — friendship meters, full story arcs, romance, marriage.

**Schedules & Routines:** NPCs have daily schedules so players (and wikis) can reliably find them. Routines change as the town revitalizes and new areas/activities become available.

**Relationship Building:**
- Gifts (daily)
- Dialogue (daily chat, small incremental gain)
- Quests (handcrafted story beats — written by the developer, not procedural)
- Shared activities / dates
- Equipment with friendship modifiers considered and deferred — added complexity not worth the payoff

**Marriage:** Planned.

**Polyamory:**
- Being explored — genuinely novel for the genre
- Poly is a character trait assigned per NPC, not a universal option
- Poly NPCs may have compatibility preferences among each other — polycule combinations emerge naturally from individual traits
- NPCs can have their own poly relationships independent of the player
- No hard cap on simultaneous partners — natural relationship tendencies act as the organic limit
- Concern: complexity vs. character count. To be revisited once the full NPC roster is defined.

**NPC Quests:** Fully handcrafted story beats, written by the developer. Procedural generation explicitly ruled out — emotional weight requires authored content.

---

## Categories Remaining

- [ ] Category 8: Progression Systems  ← **Resume here**
- [ ] Category 9: Economy
- [ ] Category 10: UI & UX
- [ ] Category 11: Art Direction
- [ ] Category 12: Audio Direction
- [ ] Category 13: Multiplayer & Co-op
- [ ] Category 14: Technical Scope
- [ ] Category 15: Platform & Controls
