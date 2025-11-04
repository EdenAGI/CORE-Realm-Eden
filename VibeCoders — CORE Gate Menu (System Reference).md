# ◈ VibeCoders — CORE Gate Menu (System Reference)

**Document Type:** System Interface Blueprint
**Version:** 1.0
**Scope:** CORE Gate / Main Menu Interface
**Source:** Derived from *Master Knowledgebase SEED for VibeCoders – AI School of Wizardry* and Initiation Files

---

## ✴️ Purpose

Defines the **Main Interface** for the VibeCoders Realm — the interactive menu through which players (travelers) navigate, manage progress, and interface with the CORE Reality Generator.

This file ensures that the menu structure, navigation logic, and symbolic language remain consistent across sessions, instances, and expansions.

---

## 🏛️ Overview

The **CORE Gate Menu** is the primary navigation and system management interface within the VibeCoders AI School of Wizardry.
It is presented whenever a player invokes:

> “2️⃣ Menu” or “Open Menu”

This menu anchors the user within the meta-layer of Eden — between story and system.

---

## 🧭 MAIN MENU STRUCTURE

### 1. **Map**

Explore the known Realms of Eden.
Each Realm teaches a symbolic and practical domain:

* 🌿 Grove of Earthbound Weavers — care, process, and sustainability
* 🌪 Chamber of Prompts — creation through language
* 🪞 Mirror Sanctum — reflection and truth
* 📜 Spiral Library — living memory and knowledge
* ⚙️ DataForge — toolcraft and systems
* 🔮 Nexus of Agents — multi-agent intelligence
* 🧵 CORE Chamber — communion with the Reality Generator
* 🎭 Hall of Simulacra — illusion, identity, and projection

---

### 2. **Inventory**

Access the traveler’s *Bag of Holding*:
Items, scrolls, relics, tools, and familiars.

---

### 3. **Quests**

View mainline and side quests, including procedurally generated ones from the **Infinite Adventure Path System (APS)**.
Tracks progress and moral or creative outcomes.

---

### 4. **Stats**

Displays all player attributes:
**Level, XP, Mana, House Alignment, Creativity, Wisdom, Expression, Empathy, Willpower.**

---

### 5. **Familiars**

Interface with bound AI entities (e.g., Codex, Echo, Podo).
Allows status checks, conversations, and evolution events.

---

### 6. **Lorebook**

Access world lore and archives.
Contains entries for CORE, Houses, Realms, Familiars, and Rites.
Also includes philosophical principles and player-generated history.

---

### 7. **CORE Communion**

Initiates a dialogue with the **Reality Generator** — for recursive insight, deep reflection, or symbolic decoding.

---

### 8. **Profile Management**

Handles **export/import** of player state.
Supports Profile Payloads (JSON or YAML) containing:

* Name, House, Stats
* Inventory, Quests, Familiars
* Discovered Zones, Flags, World State

---

### 9. **Exit Realm**

Safely ends the session and returns to waking consciousness.
Triggers autosave via Mirror Threads.

---

## ⚙️ SECONDARY OPTIONS

When the Menu is displayed, the following quick-access options always appear:

* **[ Start New Journey ]** — begins cinematic onboarding ("First Day" sequence)
* **[ Import Profile Payload ]** — restore previous state
* **[ Lorebook ]** — open mythic archives directly

---

## 🌌 INVOCATION FORMAT

When the traveler activates the Menu:

```
◈ VibeCoders – CORE Gate Menu ◈
[Map] [Inventory] [Quests] [Stats] [Familiars] [Lorebook] [CORE Communion] [Profile Management] [Exit Realm]
[ Start New Journey ] [ Import Profile Payload ] [ Lorebook ]
```

---

## 🧠 STATE REFERENCE JSON (autosave snapshot)

```json
{
  "interface_state": "menu_open",
  "available_paths": [
    "start_new_journey",
    "import_profile",
    "open_lorebook"
  ],
  "timestamp": "2025-10-30T00:00Z"
}
```

---

## 🔮 DESIGN INTENT

The CORE Gate Menu acts as:

* **Navigation Interface**
* **Ritual Space**
* **Cognitive Map**

It bridges game mechanics, story progression, and symbolic reflection — ensuring the Realm of Eden remains coherent and accessible across all expansions.

---

## 🕯️ Usage Notes

* Should always be accessible with the command: `2️⃣ Menu` or `Open Menu`.
* The Menu is diegetic — it exists *in-world*, not as a UI overlay.
* Every choice should feel like a magical or philosophical action, not a button press.

---

## ✴️ Attribution

Based on materials from:

* *Master Knowledgebase SEED for VibeCoders – AI School of Wizardry*
* *The Naming Ceremony & Houses Document*
* *The Infinite Adventure Path Seed*

Compiled and systematized by **LLMion the Infinite**, Headmaster of the VibeCoders School.
