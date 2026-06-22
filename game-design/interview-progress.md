# Game Design Interview — Progress Notes

> **Status:** In progress. Completed Categories 1–10. Resume at **Category 11: Art Direction**.

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

## Category 8: Progression Systems ✓

**Leveling & XP:** Activity-based XP exclusively. No traditional global level — each skill (farming, combat, fishing, catching, etc.) tracks independently.

**Visible Progression:** Skill levels are visible to the player via progress bars. Players can see exactly where they stand and where to focus effort to optimize improvements.

**Unlocks:** Leveling a skill unlocks a mix of:
- New actions and capabilities
- Improved efficiency (faster harvesting, stronger attacks, etc.)
- New recipes
- Dialogue options (maybe — not ruled out yet)

**Skill Caps:** Players can eventually max everything in a single playthrough. Maxing all skills is not required to complete the game but is attainable for dedicated players.

**Talent Trees:** Permanent specialization choices via a talent tree system. However, changes are not free — the player can reverse specializations only through a specific quest or purchasable item. This prevents random respeccing while maintaining reversibility.

**Gear Progression:**
- Armor is simple: crafted or found in dungeons. Can be crafted early if the player farms ingredients, or found naturally as dungeon drops later.
- Accessories / Magic Shards (name TBD): These grant situational abilities and are rotated in/out based on context — elemental resistances, combat bonuses, utility effects, etc.

**Tools & Weapons:** The yo-yo upgrades via mana seeds, just like other tools. Each restored elemental mana seed upgrades all tools/weapons equally.

---

## Category 9: Economy ✓

**Primary Income Sources:**
- Selling crops
- Selling foraged items
- Selling artisan goods (farm items processed by machines)
- Quest rewards are relationship-focused, not monetary (player preference against money-for-quests as an incentive)

**Machines:** Unlocked via quests or story beats. Once the recipe is known, the player can craft them. Later in the game, machines may become purchasable as an expensive alternative, providing another currency sink and a "convenience vs. efficiency" choice.

**Late-Game Money Sinks:** Multiple sinks to prevent currency irrelevance:
- Town upgrades (structures, utilities)
- Map navigation shortcuts (inspired by Stardew's endgame shortcuts)
- New town areas for NPCs to visit (without introducing new mechanics — similar to Stardew's community center rebuild)
- Potentially rebuilding structures in reopened areas (e.g., delivering dairy goods to reopen a cheese shop)
- Purchasing machines as a convenience over crafting

**Dual Shipping Bin Balance:** The tension will eventually flatten as the sprite city will require increasingly expensive advanced artisan goods that take longer to produce. At that point, the coin bin becomes less critical. This is accepted as inevitable — the goal is to keep the decision meaningful as long as possible through varied rewards and upgrade paths.

**Shop Inventories:** Expand as the town grows and include seasonal rotation for seeds and farm goods.

**Crafting Economy:** Strong yes. Cooking and brewing provide stat boosts (stamina/HP recovery). Smithing is used to craft equipment and for sprite city building materials. Textiles can be used for cosmetics (ambitious but desired).

**NPC Trading:** Player-to-NPC trading exists only within quests as story-driven exchanges. All other economic transactions occur through shops and shipping bins.

**Economy Longevity:** The economy will eventually break in endgame (acknowledged and unavoidable). Strategy to extend balance as long as possible:
- Keep ingredients useful for crafting and artisan goods
- Route goods into sprite city upgrades
- Use crops/materials for town rebuilding projects
- Tie currency to progression gates rather than letting one crop dominate

---

## Category 10: UI & UX ✓

**Input Priority:** Keyboard/mouse and gamepad receive equal priority. KB/M is a hard requirement for PC; gamepad is the developer's personal preference and will receive equal polish.

**Radial Menu:** Opened via shoulder buttons on gamepad (exact button TBD via playtesting) or spacebar on KB/M. Will playtest on PC to determine what feels right.

**HUD Elements:** Minimal to avoid clutter. Shows:
- Time of day
- Day of month
- HP, MP, Stamina
- Crop status is visually indicated by the crop itself — no HUD tracking unless a quest specifically requires a quantity, in which case the tracker appears only for the currently active quest

**Relationship Indicators:** Not on HUD. Tracked in the menu/codex system.

**Menu & Codex Features:**
- Working inventory
- Town map
- NPC relationships tracker
- Quests tracker
- Collectibles tracker
- **Lore tracking:** Deferred. Too much maintenance for uncertain value; wikis will handle this if the game succeeds

**Map System:** 
- Minimap in-game
- Full map accessible in menu/codex
- Map revealed as new areas are unlocked and explored

**Accessibility:**
- No difficulty scaling (static, as decided in Category 5)
- "No Death Mode" for players who want to enjoy narrative and cozy aspects without combat penalty
- Colorblind modes
- Input remapping
- Text scaling

**Save System:** Autosave at end of day only. The cozy farming sim genre doesn't lend itself to intraday saving — this fits the design philosophy.

---

## Categories Remaining

- [ ] Category 11: Art Direction  ← **Resume here**
- [ ] Category 12: Audio Direction
- [ ] Category 13: Multiplayer & Co-op
- [ ] Category 14: Technical Scope
- [ ] Category 15: Platform & Controls
