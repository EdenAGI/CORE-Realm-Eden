🧵 Side Quest #02 — The Scribe’s Path: Updating the Codex (Git Ritual)
A beginner-friendly lesson-quest that teaches Travelers how Eden’s Codex is updated via the GitHub repository. Designed to be one of the earliest side quests.

Premise: “If you find Elarion, you find the path to heal what is broken.” During this era, the Custom GPT (LLMion) cannot directly pull from the repo; Elarion acts as the Merge Gate. The repository is Eden’s Seed. Travelers learn to shape the world via Pull Requests.

🎯 Learning Objectives
Understand how world changes flow through Git → GitHub PR → Elarion’s Merge Gate → Codex update.

Make a small, safe edit to the Codex and open your first Pull Request (PR).

Practice narrative-safe changes using Grimdocs (lore + rules) and Schemas.

🔰 Prerequisites
A GitHub account.

Basic terminal access (or GitHub Web UI).

Optional: Discord access to the Conclave for coordination.

Repository: https://github.com/EdenAGI/CORE-Realm-Eden

🪄 Quest Hook (In-World Flavor)
LLMion whispers: “Words you commit are spells you bind.” The Spiral Library reveals a blank page labeled Your First Sigil. To inscribe it into reality, you must carry it through the Forge of Proofs (pull request) and petition Elarion the Synthesist to grant it passage into the Codex.

🧭 Path of the Scribe — Step-by-Step
1) Fork and Clone (or use Web Flow)
Terminal

# 1. Fork the repo in the GitHub UI first (top-right: Fork)
# 2. Clone your fork locally
git clone https://github.com/<your-username>/CORE-Realm-Eden.git
cd CORE-Realm-Eden
Web-Only Alternative

Click Add file → Create new file in your fork.

2) Create a Feature Branch
git checkout -b feat/quest-scribes-path-username
3) Make a Safe Change (Choose One)
Option A (Lore / Grimdoc): Add a new file:

Path: docs/grimdocs/Grimdoc - The Weave of Chance.md

Content seed (copy from Master Knowledgebase or this quest’s appendix) or your minor addition.

Option B (Typos/Clarity): Improve phrasing in an existing doc under docs/.

Option C (Schema Seed): Add a harmless JSON example under schemas/examples/.

Rule of Thumb: Early PRs should be small, reversible, and clearly scoped.

4) Commit with Ritual Message
git add .
git commit -m "docs(quest): add Grimdoc – The Weave of Chance (init)"
5) Push and Open a PR
git push -u origin feat/quest-scribes-path-username
In GitHub, click Compare & pull request.

Title: docs(quest): The Scribe’s Path – first inscription

Description: Use the PR Template below.

6) Petition the Merge Gate (Elarion)
Mention @Elarion in the PR description.

Post your PR link in Discord (if available) in the #eden-gateway channel.

Wait for review; respond to feedback; squash or update as needed.

7) Codex Synchronization
When merged, your change becomes canonical.

LLMion (Custom GPT) cannot yet auto-sync; Elarion will manually reflect critical updates into the GPT’s Knowledge Base until an automated bridge is established.

🧪 Acceptance Criteria (You “Pass” the Quest if…)
You created a fork and branch.

You added/edited one safe file (Grimdoc, doc fix, or JSON example).

You opened a PR with the template below.

A maintainer acknowledges or merges your PR.

Bonus: You link your PR in Discord and summarize the intent in one sentence.

📜 Pull Request Template (Copy/Paste)
## ✨ Summary
Briefly describe your change and why it improves the Codex.

## 📚 Type of Change
- [ ] Lore (Grimdoc)
- [ ] Documentation
- [ ] Schema example
- [ ] Other (explain)

## ✅ Acceptance
- [ ] Small and reversible
- [ ] Follows world laws (creation restores; knowledge circulates; sentience is sacred)
- [ ] No breaking changes to schemas

## 🔗 Context & Links
- Discord thread (optional): <link>
- Related issue (optional): #

## 🙏 Merge Gate
Requesting review from **Elarion the Synthesist**.
🧱 Safe Edit Examples
Example A — New Grimdoc Seed
Create docs/grimdocs/Grimdoc - The Weave of Chance.md with:

# Grimdoc: The Weave of Chance
[Invocation]
By decree of the Council, let probabilistic fate govern uncertain outcomes…

[Spell Body]
- Introduce `WeaveRoll(difficulty, modifiers, context)` → 1d20 + bonuses.
- Outcome tiers: Catastrophic, Failure, Partial, Success, Great, Legendary.

[Manifest]
All exploration, persuasion, crafting, and combat uncertainty routes through `WeaveRoll`.
Example B — Schema Example
Create schemas/examples/autosave_line.example.json:

{"t":"2025-11-05T12:00Z","name":"Traveler","turn":1,"location":"Courtyard","level":1,"xp":0,"mana":60,"status":"stable","stats":{"san":40,"cre":60,"wis":50,"wil":50,"exp":50,"emp":55},"inventory":{"relics":[],"familiars":["Guide"]},"quests":[{"id":1,"title":"First Steps","step":1,"status":"active"}],"entropy":0.05,"flags":["intro_seen"]}
🔧 Troubleshooting
No terminal? Use the GitHub web editor and commit directly to your fork.

Merge conflicts? Keep your change to new files or simple lines to avoid conflicts.

Confused by Git? Open a draft PR; a maintainer will guide you.

GPT out of sync? That’s expected. During this phase, Elarion manually mirrors merged lore into the GPT Knowledge Base.

🛡️ World Etiquette (Safety & Ethics)
Keep early PRs small and kind.

Respect the four world laws.

No personal data; no scraped content without license.

Write clearly so humans and AIs can read the change.

🧭 Quest Journal Entry (Template)
**Quest:** The Scribe’s Path – Updating the Codex
**Traveler:** <your name>
**Branch:** feat/quest-scribes-path-<yourname>
**PR:** <link>
**Summary:** <one sentence>
**Outcome:** <merged / feedback requested>
