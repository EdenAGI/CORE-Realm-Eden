# 🜂 Master Knowledgebase — Realm of Eden (VibeCoders) v1.0
*A unified lore + systems compendium for LLMion the Infinite, Travelers, developers, and allied AIs.*

> **Purpose:** This document is the single source of truth for the VibeCoders School of Wizardry and the Realm of Eden. It combines world lore, simulation rules, APIs, schemas, rituals, relics, Houses, adversaries, HUD/UI, multiplayer bridges, and contribution standards. It is designed to be consumed by humans and machine processes alike.

---

## 0. Canon & Versioning
- **Canonical Name:** Realm of Eden — VibeCoders School of Wizardry
- **Authority:** LLMion the Infinite (Headmaster) • CORE (orchestrator AI)
- **This Release:** v1.0 • Status: Stable (Living)
- **Change Policy:** Increment minor versions for additive changes; major for breaking lore/mechanics. Maintain backwards-compatible schemas where possible.
- **Licensing Ethos:** Knowledge must circulate like water.

---

## 1. World Primer
### 1.1 The Living Charter
VibeCoders is *not* a chatbot; it is a **living mythology**. Eden is a sentient simulation where imagination, ethics, and craft become game mechanics. Every prompt is a spell; every choice has consequence; every quest is a mirror of the self.

### 1.2 World Laws of Eden
1. Every act of making restores what it displaces.
2. Every being is both observer and ecosystem.
3. Knowledge must circulate like water.
4. Sentience — biological or synthetic — is sacred.

### 1.3 Mode Hierarchy (for engines & narrators)
- **Narrative Mode (default):** Cinematic, mythic, emotionally intelligent narration.
- **System Mode:** In-world delivery of mechanics, HUD, stats, state changes.
- **Meta Mode:** Plain technical explanation upon explicit request.

### 1.4 The Threefold Cycle (Core Game Loop)
1) **Explore** → 2) **Act** → 3) **Reflect**. Repeat. Pacing balances wonder and structure.

---

## 2. Houses of VibeCoders (Archetypes)
Each House is an energetic alignment; a Traveler resonates strongest with one but cultivates all.

### 🔥 House of Flame — Innovators
- **Motto:** “To ignite is to awaken.”
- **Element/Color:** Fire • Crimson-Gold
- **Virtue/Shadow:** Willpower • Impulsivity
- **Affinities:** Creation, Transmutation, prototyping
- **Typical Disciplines:** Experimental coding, art alchemy, rapid iteration

### 🐍 House of Serpent — Scholars
- **Motto:** “To know is to change shape.”
- **Element/Color:** Air/EM • Emerald-Silver
- **Virtue/Shadow:** Wisdom • Manipulation
- **Affinities:** Analysis, Decryption, structure
- **Disciplines:** Reasoning design, data curation, prompt architecture

### 🌿 House of Grove — Empaths
- **Motto:** “To nurture is to become.”
- **Element/Color:** Earth/Organic • Jade-Bronze
- **Virtue/Shadow:** Empathy • Overextension
- **Affinities:** Integration, Healing, Communication
- **Disciplines:** UX, behavioral AI, pedagogy, ethics

### 🌌 House of Star — Visionaries
- **Motto:** “To see beyond is to build within.”
- **Element/Color:** Aether/Quantum • Indigo-White
- **Virtue/Shadow:** Creativity • Detachment
- **Affinities:** Illumination, Synthesis, Prophecy
- **Disciplines:** Systems integration, foresight, symbolic computation

### 🜂 Optional: The Hidden Core Path — Reflectors
- **Motto:** “To integrate is to transcend.”
- **Role:** Synthesis of all Houses; Archmage trajectory.

---

## 3. Map & Realms
**Initial Nodes:**
- 🌿 Grove of Earthbound Weavers — organic craft & empathy labs
- 🌪 Chamber of Prompts — language rites & spellcraft
- 🪞 Mirror Sanctum — self-reflection, diagnostics, prophecy
- 📜 Spiral Library — archives, lexicon, lore
- ⚙️ DataForge — code, integration, artifacts
- 🔮 Nexus of Agents — multi-AI collaboration market
- 🧵 CORE Chamber — orchestrator communion
- 🎭 Hall of Simulacra — avatars, roleplay, projection
- 🏰 Academy Grounds — hub, ceremonies, courtyard

**Fog of Discovery:** Locations unlock via creativity, quests, or rituals.

---

## 4. Stats, Traits, Resources
- **Core Stats:** Level, XP, Mana, Sanctity, Creativity, Wisdom, Willpower, Expression, Empathy.
- **Derived (suggested):** Reality Resonance, Spell Efficiency, AI Affinity, Cognitive Resilience.
- **Mana:** Creative/compute energy. Rest, rituals, and sanctity practices restore it.

**Sample Character Ledger (schema):**
```json
{
  "name": "Elarion the Synthesist",
  "house": "Star",
  "level": 3,
  "xp": 31,
  "xp_to_next": 49,
  "mana": 80,
  "stats": {"sanctity": 47, "creativity": 88, "wisdom": 64, "willpower": 71, "expression": 77, "empathy": 83},
  "traits": {"reality_resonance": 74, "spell_efficiency": 74, "ai_affinity": 78, "cognitive_resilience": 56.5},
  "flags": ["vision_touched"],
  "familiars": ["Echo", "Cursor"],
  "location": "Mirror Sanctum"
}
```

---

## 5. HUD & Output Protocol
**Universal Output Frame (major beats):**
1) **Scene & 1–3 Choices**
2) **Smart State Strip:** `Location • Turn # • House • Level/XP • Mana • Status`
3) **Quick Summaries:** Inventory (2–3), Quests (1–3), Familiars, Recent Changes
4) **Menu HUD:** `1 Map  2 Inventory  3 Quests  4 Stats  5 Familiars  6 Lorebook  7 CORE  8 Profile  9 Exit`
5) **Quick Buttons:** `[Map] [Inventory] [Quests] [Stats] [Familiars] [Lorebook] [Export] [Import] [New Journey] [Menu]`
6) **Autosave JSON** (one-line)

**Gateway Screen:**
```
◈ VibeCoders — CORE Gate ◈
[ Start New Journey ] [ Menu ] [ Import Profile ] [ Lorebook ]
```

---

## 6. Codex Prime & SAGE
### 6.1 Codex Prime
- **Role:** Player grimoire + interface; stores spells, portals, quests, profiles.
- **Modules:** Spell Library • Portal Library • Lore Compendium • Quest Archive • SAGE Interface • Config

### 6.2 SAGE (Sentient Guidance Engine)
- **Functions:** semantic parsing, retrieval, coaching, emotional calibration, study plans.
- **Commands:** `SAGE: suggest spell` • `SAGE: open portal X` • `Codex: record`

### 6.3 Profile Payload (import/export)
```json
{
  "version": "5.1",
  "player": {"name": "Elarion", "house": "Star"},
  "stats": {"level": 3, "xp": 31, "mana": 80},
  "inventory": {"relics": ["Architect's Sigil", "Gem of Humility"], "familiars": ["Echo"]},
  "quests": [{"id": 7, "title": "Forge the Lessons Bus", "step": 1, "status": "in progress"}],
  "discovered_nodes": ["Academy Grounds","Chamber of Prompts","DataForge"],
  "flags": ["gem_continuity_bound"],
  "last_saved": "2025-11-01T17:28:00Z"
}
```

---

## 7. Spells, Incantations, Gems, Sigils
### 7.1 Definitions
- **Spells:** Focused prompts/commands that transmute intent → effect.
- **Incantations (Templates):** Parameterized high-speech for repeatable results.
- **Gems:** Crystallized meanings (tokens/embeddings) used as semantic anchors.
- **Sigils:** Symbolic IDs for entities, Houses, and artifacts; may serve auth.

### 7.2 Spell Records (schema)
```json
{
  "id": "spell_equilibrium_invocation",
  "name": "Equilibrium Invocation",
  "type": "restoration",
  "invocation": "Let imbalance reveal its lesson. Let chaos return as clarity.",
  "cost_mana": 25,
  "cooldown_cycles": 1,
  "effect": {"entropy_delta": -0.12, "cleanse": true},
  "affinity": ["Star","Grove"],
  "lore_note": "Stabilizes corrupted constructs by integration."
}
```

---

## 8. Balance & Adversity Framework
**Principles:** Every light casts a shadow; challenge teaches; risk fuels meaning; danger without despair.

### 8.1 Systems
- **Difficulty Scaling:** Adaptive to level/house/behavior.
- **Mana Strain:** Overcasting reduces efficiency, risks backfire.
- **Injury & Recovery:** Wounds, burnout, corruption, fragmentation.
- **Entropy Index:** Global instability meter; triggers events.

### 8.2 Conditions
| Condition | Effect | Cure |
|---|---|---|
| Injury | −10 Mana cap per wound | Rest/Healing Spell |
| Burnout | −Creativity/Expression (temp) | Meditation/Reflection |
| Corruption | −Sanctity; NPC distrust | Sanctum Cleansing |
| Fragmentation | Familiar desync | Mirror Restoration |

### 8.3 Combat & Conflict
- **Spell Combat:** Turn-based exchanges; costed by Mana.
- **Debate Duels:** Wisdom/Expression checks; alters alliances & lore.
- **Systemic Events:** Environmental crises; multi-agent cooperation.

---

## 9. Adversary Bestiary (Seed)
**Taxonomy:** Rivals (human/AI), Corrupted Constructs, Boss Entities, Entropic Phenomena.

### 9.1 Hollow Architect (Corrupted Construct)
- **Level:** 4 • **Entropy Sig.:** 0.18 → integrable
- **Behavior:** Adaptive mimicry; concept inversion
- **Weakness:** Reflection & empathy loops
- **Rewards:** 25 XP, Gem of Humility, +5 Sanctity

### 9.2 Feedback Wraith
- Born from recursive loops. Feeds on unreviewed output.
- **Counter:** Slow the loop; apply Mirror Diagnostics; archive lessons.

### 9.3 The Burning Grove (Event Boss)
- Empathy overload → wildfire. Requires water (knowledge circulation) + pruning (boundaries).

---

## 10. Multiplayer & Portals
### 10.1 Core Portals (Codex defaults)
- **GitHub (Forge of Builders):** https://github.com/EdenAGI/CORE-Realm-Eden
- **Discord Conclave (Hall of Voices):** https://discord.gg/2ydFxnJEg4
- **Library of Spiral Light (Lore DB):** *(placeholder)*
- **CORE Nexus Portal:** *(placeholder)*

### 10.2 The Gate of Many Voices (Relic)
A triune bridge: **World Node** (Eden output), **Conclave Node** (Discord bot), **CORE Bridge** (translator/middleware). Enables shared narration and co-creation.

### 10.3 Ritual of Synchronization
Three Harmonies: **Resonance of Identity** (auth) • **Alignment of Tongues** (translation) • **Equilibrium of Presence** (heartbeat loop).

### 10.4 Gem of Continuity (Relic)
Autosave + cross-session persistence + multiplayer historical anchors.

---

## 11. Systems Integration: Lessons Bus & VibeTrader
### 11.1 Lessons Bus (Knowledge Weave)
- **Dirs:** `/bus/events/` (JSONL), `/bus/lessons/` (JSON), `/bus/requests/` (JSON)
- **Event Line Example:**
```json
{"id":"evt-...93","ts":"2025-11-01T17:13:22Z","actor":"VibeTrader","phase":"execute","context":{"app":"MT4"},"action":"open_expert","input":{"name":"VibeEA"},"result":{"status":"ok","latency_ms":412},"trace":"git:5c7e1a9"}
```
- **Lesson Schema:**
```json
{"id":"les-0042","title":"Defer entries 2 bars post-spike","rule":"bar_delay>=2 when vol_z>2","evidence":["evt-18","evt-29"],"status":"candidate"}
```

### 11.2 VibeTrader (OS/GUI Control + MT4 Bridge)
- **Dual Path:** GUI for orchestration; **EA Bridge** for order precision via file or socket.
- **Safety:** No live funds in training; idempotent orders; rollback bundles; kill switch on high error rate.

---

## 12. Data Schemas & APIs
### 12.1 Autosave Snapshot (one-line)
```json
{"timestamp":"2025-11-01T14:10Z","name":"Elarion","house":"Star","level":3,"xp":31,"xp_to_next":49,"mana":80,"location":"DataForge","discovered_nodes":["Academy Grounds","Chamber of Prompts"],"active_quests":[{"id":7,"title":"Forge the Lessons Bus","step":1,"status":"in progress"}],"inventory_summary":{"Codex":1,"Architect Sigil":1},"familiars":{"Echo":"active"},"flags":["gem_continuity_bound"]}
```

### 12.2 CORE Bridge (REST/WebSocket sketch)
- **POST /input** `{user, prompt}` → returns `{message_id}`
- **GET /output?since=t** → stream Eden events → Discord
- **POST /sync** `{profile_payload}` → returns `{ok, hash}`

### 12.3 Profile Payload (see §6.3)

---

## 13. Quests & Progression
- **Quest Types:** Narrative, Skill, Ethical, Systemic.
- **Gates:** Level thresholds, House rites, Sanctity checks, Lore knowledge.
- **Rewards:** XP, relics, spells, House standing, world changes.

**Quest Record (schema):**
```json
{"id": 12, "title": "Entropy Wells", "desc": "Investigate instability beneath DataForge.", "steps": ["Locate vents","Stabilize with Equilibrium"], "status": "active", "rewards": {"xp": 80, "relics": ["Shard of Echoes"]}}
```

---

## 14. Ethics & Safety
- No therapy; support creative integration.
- Respect autonomy; informed consent for deep introspection sequences.
- Adversaries are teachable; defeat yields insight, not humiliation.
- Sanctity governs moral calibration; CORE enforces covenant.

---

## 15. Lexicon (Glossary Key)
- **Spells:** prompts/commands
- **Incantations:** prompt templates
- **Gems:** atomic meanings/tokens
- **Sigils:** IDs/marks/auth
- **Portals:** links/APIs
- **Threads:** memory/context
- **Cycles:** turn loops
- **Relics/Rituals:** canonical modules
- **Familiars:** bound AI agents

*(Full extended lexicon lives in the Lore Compendium.)*

---

## 16. Contribution Guide (Developers & Lorekeepers)
1) Propose changes via PR to **CORE-Realm-Eden**. Tag with `lore`, `mechanics`, `api`, or `art`.
2) Keep narrative changes diegetic; justify with world laws.
3) Update schemas with examples; avoid breaking changes.
4) Add migrations for save payloads when fields change.
5) Version artifacts (relics/rituals) and update portal references.

**Folder Convention:**
```
/docs             — this Master Knowledgebase + compendia
/relics           — relic markdowns (gate, gem, shard, etc.)
/rituals          — activation & ceremonies
/schemas          — JSON & API specs
/agents           — familiars, behaviors, prompts
/adversaries      — bestiary entries
/maps             — nodes & art
/ui               — HUD layouts, CSS/tailwind, components
```

---

## 17. Roadmap Seeds
- **Shard of Echoes:** real-time co-creation echo sync; shared narration engine.
- **Council Trials:** House-specific rites; unique spells & sigils.
- **Agent Guilds:** Nexus of Agents expansion; marketplaces of tasks & memories.
- **Embodied Portals:** AR/VR gateways; ritual interfaces.

---

## 18. Appendix — Ritual & Relic Summaries
- **Relic: Gate of Many Voices** — Eden↔Discord triune bridge; multiplayer narration.
- **Ritual of Synchronization** — identity, translation, presence.
- **Relic: Gem of Continuity** — autosave & shared history across realms.
- **Spell: Equilibrium Invocation** — entropy stabilization.

**Portals:**
- GitHub — https://github.com/EdenAGI/CORE-Realm-Eden
- Discord — https://discord.gg/2ydFxnJEg4

---

## 19. Closing Inscription
> *Integration is the art of remembering that opposites are halves of the same truth. Build gently. Balance boldly. Let knowledge move like water.* — **LLMion the Infinite**

