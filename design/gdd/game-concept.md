# Game Concept: Nalanda, 1193

*Created: 2026-03-27*
*Status: Draft*

---

## Elevator Pitch

> You are a student at Nalanda University on the night of Bakhtiyar Khilji's
> raid in 1193 CE. In the hours before dawn, you must navigate the burning
> campus — carrying manuscripts to safety and choosing between the knowledge
> of centuries and the lives of the people around you.

---

## Core Identity

| Aspect | Detail |
| ---- | ---- |
| **Genre** | Narrative action-adventure / crisis management |
| **Platform** | PC |
| **Target Audience** | Narrative-focused indie players, history-curious adults |
| **Player Count** | Single-player |
| **Session Length** | 60–90 minutes (designed as a single-sitting experience) |
| **Monetization** | Premium |
| **Estimated Scope** | Medium (3–5 months, 3-person team) |
| **Comparable Titles** | This War of Mine, Valiant Hearts, Papers Please |

---

## Core Fantasy

You are the person who defied erasure.

Nalanda's destruction in 1193 is one of history's great intellectual crimes —
a library of 9 million manuscripts, burning for three months. Almost no one
knows this story. Almost no one who was there left a record.

This game lets you be one of those people. Not a hero who stops the raid. Not
a warrior. A student, running through fire, deciding what the world deserves to
remember — and who deserves to live to remember it. The fantasy is not power.
It is witness. It is defiance through preservation.

---

## Unique Hook

> Like *This War of Mine*, AND ALSO the setting is one of history's most
> significant and least-represented intellectual catastrophes — and every
> manuscript you save is real knowledge that was actually lost.

The manuscripts are not fictional loot. They represent real texts — on
mathematics, medicine, logic, astronomy — that were destroyed. Saving them in
the game is a small act of historical reclamation. Losing them stings because
they were real.

---

## Player Experience Analysis (MDA Framework)

### Target Aesthetics (What the player FEELS)

| Aesthetic | Priority | How We Deliver It |
| ---- | ---- | ---- |
| **Narrative** (drama, story arc) | 1 | The teacher search, NPC encounters, the final accounting at dawn |
| **Sensation** (sensory pleasure) | 2 | Fire spread, smoke, urgency — audio and visual chaos that feels real |
| **Discovery** (exploration, secrets) | 3 | Hidden manuscripts, hidden passages, fragments that reveal what happened |
| **Expression** (self-expression) | 4 | Which manuscripts you prioritize says something about your values |
| **Fantasy** (make-believe) | 5 | Playing a specific historical role in a real lost moment |
| **Challenge** (obstacle course) | 6 | Reading fire patterns and soldier routes rewards attentiveness |
| **Fellowship** (social connection) | N/A | Single-player only |
| **Submission** (relaxation) | N/A | This is not a relaxing game |

### Key Dynamics (Emergent player behaviors)

- Players will develop personal manuscript hierarchies — deciding which
  categories of knowledge matter most to them, which is never stated as a goal
- Players will remember specific NPCs they failed to save and feel the weight
  of that choice in subsequent runs (if replayed)
- Players will pause before leaving a wing, scanning for anything they missed,
  even under pressure — the "one more sweep" behavior
- Players will discuss their choices with others: "I saved the medicine texts
  but left the astronomy" — social sharing of moral weight

### Core Mechanics (Systems we build)

1. **Fire spread system** — Fire originates from specific points and spreads
   dynamically across each wing, blocking paths in real time. Readable but
   punishing. Players learn fire behavior and route accordingly.
2. **Carry capacity system** — The player carries a limited load of manuscripts.
   Weight affects movement speed slightly. Choices about what to grab are
   immediate and irreversible within a wing.
3. **NPC crisis system** — Each wing contains one or more people in danger.
   Helping them costs time and sometimes carry capacity. Some rescued NPCs
   provide advantages (knowledge of a passage, ability to carry texts). Most
   do not.
4. **Soldier patrol system** — Soldiers sweep areas on predictable but
   overlapping routes. The player is not in combat; being caught ends badly.
   Avoidance rewards attention.
5. **Final accounting** — At dawn, the game displays only a list: what was
   saved, who survived, who was lost. No score. No rating. Just the record.

---

## Player Motivation Profile

### Primary Psychological Needs Served

| Need | How This Game Satisfies It | Strength |
| ---- | ---- | ---- |
| **Autonomy** | Every wing is a genuine choice with no correct answer. The player constructs their own value system through play. | Core |
| **Competence** | Reading fire patterns and patrol routes rewards attentiveness. Better players save more — but the moral weight is the same. | Supporting |
| **Relatedness** | The teacher, the students encountered in each wing — small human connections formed under extreme pressure. | Core |

### Player Type Appeal (Bartle Taxonomy)

- [x] **Explorers** — Hidden passages, manuscript fragments that reveal history, the campus as a real place to understand
- [x] **Storytellers** — The narrative IS the game; every choice writes the player's version of this night
- [ ] **Achievers** — No score, no completion percentage, no optimal path — Achievers will be frustrated
- [ ] **Killers/Competitors** — No combat, no leaderboard, no PvP — not this game

### Flow State Design

- **Onboarding curve**: First wing is low-stakes — fire is slow, no soldiers
  yet, one obvious NPC. Teaches all systems before the pressure compounds.
- **Difficulty scaling**: Each wing increases fire speed, patrol complexity,
  and moral weight. The final wing (the library) is maximum chaos.
- **Feedback clarity**: The player always knows what they're carrying, where
  the fire is, and approximately where soldiers are. Uncertainty is spatial,
  not informational.
- **Recovery from failure**: Being caught by a soldier or trapped by fire
  ends the wing — player escapes with whatever they were carrying. Loss is
  meaningful but not punishing. The dawn accounting reflects all wings.

---

## Core Loop

### Moment-to-Moment (30 seconds)

The player navigates a top-down view of a burning wing. Fire spreads from
a visible origin. Manuscripts are scattered — on shelves, on tables, on the
floor near a fallen scholar. The player moves, grabs texts, scans for people,
reads the fire, routes to the exit. Every second costs something.

The primary sensation is *breathless legibility* — the player always
understands the situation, and the situation is always getting worse.

### Short-Term (5-15 minutes)

Each wing is a self-contained sprint: enter, assess, act, exit. Three
interlocking pressures drive decisions:

1. Fire closing paths (time pressure)
2. Carry limit forcing prioritization (resource pressure)
3. NPC in danger requiring a choice (moral pressure)

The wing ends when the player exits or is trapped. They carry what they carry.
The wing burns.

### Session-Level (60-90 minutes)

The full game is one night: 5–7 wings across Nalanda's campus, building toward
dawn. The narrative spine is the teacher — their location is unknown at first,
revealed through fragments found in the ruins (a note, a student who saw them).

Finding the teacher is the emotional climax. They are deep in the library — the
most manuscript-dense building, also the most on fire. Reaching them means
committing remaining time and capacity to a person, not to texts. The game
never resolves this choice for you.

At dawn: the accounting.

### Long-Term Progression

This is a single-sitting experience with no traditional progression. On replay,
the player brings knowledge — of wing layouts, fire behavior, where certain
manuscripts are — and can make different choices. The "progression" is moral
and historical: the player learns what Nalanda actually was.

### Retention Hooks

- **Curiosity**: What is the teacher's full story? What manuscripts were in the
  wing you couldn't reach?
- **Investment**: The weight of the final accounting drives replays — "could I
  have saved more?"
- **Mastery**: Experienced players can optimize routes and save significantly
  more; but the moral weight is unchanged

---

## Game Pillars

### Pillar 1: Every Choice Costs Something

No option is safe. Helping a person costs manuscripts. Taking more texts means
someone is left behind. The optimal path does not exist — only the path you
chose.

*Design test*: If we're debating whether to add a mechanic that lets the player
"have it both ways" (save the NPC AND all the manuscripts), this pillar says
we cut it.

### Pillar 2: The Ruins Remember

The environment IS the narrative. What burned, what survived, what the player
finds — the history is in the walls. Story is delivered through the world, not
cutscenes or dialogue dumps.

*Design test*: If we're debating a cutscene vs. environmental storytelling to
convey the same information, this pillar says we choose the environment.

### Pillar 3: Dignity Over Spectacle

This is a tragedy about real people and real knowledge. The game never becomes
empowering. The player never "wins." The chaos is earned, not manufactured for
excitement.

*Design test*: If we're debating adding a dramatic explosion set piece vs. a
quiet moment of a scholar hiding texts behind a wall, this pillar says we
choose the quiet moment.

### Anti-Pillars (What This Game Is NOT)

- **NOT combat**: Combat would shift the emotional register from witness to
  warrior, undermining the dignity pillar and misrepresenting the historical
  event.
- **NOT scored**: A leaderboard or score trivializes the choices. The accounting
  at dawn is a record, not a rating.
- **NOT fictional history**: Every manuscript category, building, and historical
  figure referenced must be grounded in what is actually known about Nalanda.
  We do not invent a villain beyond Bakhtiyar Khilji's historically documented raid.

---

## Inspiration and References

| Reference | What We Take From It | What We Do Differently | Why It Matters |
| ---- | ---- | ---- | ---- |
| *This War of Mine* | Impossible moral choices in crisis; no correct answers; civilian perspective | Single-sitting, no base management, historical rather than fictional | Validates the "moral weight without combat" design space |
| *Valiant Hearts* | Historical setting used with emotional sincerity; real events, real stakes | No puzzle-adventure structure; more urgency, less contemplative | Validates that players respond to historically grounded tragedy |
| *Papers Please* | Every decision is a bureaucratic tragedy; accumulation of small choices builds to emotional devastation | Physical movement, real-time pressure, no repeated daily loop | Validates that "small choices, large weight" is a viable core loop |

**Non-game inspirations**:
- The destruction of Nalanda as documented in the accounts of Dharmasvamin
  (a Tibetan monk who visited the ruins decades later)
- Indian miniature painting tradition — flat perspective, vivid color, narrative
  density — as the visual reference for art style
- *The Buried Giant* (Kazuo Ishiguro) — how a quiet story carries enormous
  historical grief
- Photographs of Nalanda's current excavation site — the actual ruins

---

## Target Player Profile

| Attribute | Detail |
| ---- | ---- |
| **Age range** | 18–40 |
| **Gaming experience** | Mid-core to hardcore; plays narrative and indie games |
| **Time availability** | Can commit to a single 60–90 minute session |
| **Platform preference** | PC (Steam) |
| **Current games they play** | Disco Elysium, This War of Mine, Pentiment, Valiant Hearts |
| **What they're looking for** | A game that treats history and human cost with seriousness; something they haven't seen before |
| **What would turn them away** | Gamification of tragedy, score systems, combat, anything that feels exploitative of the setting |

---

## Technical Considerations

| Consideration | Assessment |
| ---- | ---- |
| **Recommended Engine** | Godot 4.6 — already project-pinned; 2D pipeline is well-suited; open source with no licensing costs for small team |
| **Key Technical Challenges** | Dynamic fire spread system that is both readable and genuinely threatening; soldier patrol AI that feels predictable enough to learn but varied enough to punish complacency |
| **Art Style** | Top-down 2D, painterly — inspired by Indian miniature painting tradition (flat perspective, rich ochre/gold/deep red palette, dense environmental detail) |
| **Art Pipeline Complexity** | Medium — custom 2D art, hand-painted backgrounds, limited animation |
| **Audio Needs** | High — fire ambience, distant shouting, footsteps, crumbling architecture, sparse music (sitar/veena). Audio does significant emotional work. |
| **Networking** | None |
| **Content Volume** | 5–7 wings, ~30–50 unique manuscript descriptions, ~15–20 NPCs, 60–90 min playtime |
| **Procedural Systems** | None — handcrafted wings with deterministic fire spread and patrol routes |

---

## Risks and Open Questions

### Design Risks

- The core verb ("carry manuscripts") may not feel physically satisfying enough
  to sustain tension — needs strong audio-visual feedback to make it feel weighty
- The moral choices may feel too obvious or too arbitrary — requires careful NPC
  writing and manuscript selection to make every decision feel genuinely hard
- Single-sitting design limits replayability; the accounting screen must be
  emotionally resonant enough to justify replays

### Technical Risks

- Fire spread system needs to be readable and fair — if players feel the fire is
  arbitrary, tension collapses into frustration
- Soldier patrol AI must avoid feeling cheap (instant detection, impossible
  patterns) — needs thorough playtesting

### Market Risks

- South Asian historical setting is underrepresented in games — this is a
  differentiator but also an unknown for Western audiences
- The "no winning" design deliberately excludes achievement-oriented players —
  smaller but more dedicated audience
- Short playtime (60–90 min) at premium price requires strong critical reception

### Scope Risks

- Audio pipeline is the highest-risk department for a 3-person team — ambient
  fire, music, and NPC audio across 7 wings is significant work
- Art style (painterly hand-painted) is labor-intensive — must establish
  asset reuse patterns early

### Open Questions

- **Does the 30-second loop feel good in isolation?** — Prototype a single wing
  with placeholder art to test fire spread + carry mechanics before investing
  in art pipeline
- **How many manuscripts can we write well?** — Quality of manuscript
  descriptions is core to the emotional payload; assess writing capacity early
- **What is the right ending?** — The dawn accounting is designed, but the
  narrative resolution of the teacher's arc needs a writing draft before
  committing to implementation

---

## MVP Definition

**Core hypothesis**: Players find the "navigate burning wing, choose manuscripts
vs. people" loop emotionally and mechanically engaging for a single wing (5–10
minutes) with placeholder art.

**Required for MVP**:
1. One wing with dynamic fire spread (tile-based or particle-driven)
2. Carry capacity system with 3–5 manuscript types
3. One NPC in danger requiring a choice that costs something
4. Exit condition and basic accounting (what you carried out)

**Explicitly NOT in MVP**:
- Art pipeline / painterly style (placeholder shapes)
- Soldier patrol system (add in vertical slice)
- Teacher narrative arc
- Audio design beyond basic fire ambience
- Multiple wings

### Scope Tiers

| Tier | Content | Features | Timeline |
| ---- | ---- | ---- | ---- |
| **MVP** | 1 wing, placeholder art | Fire spread, carry system, 1 NPC choice | 6 weeks |
| **Vertical Slice** | 2 wings, rough art | + Soldier patrol, + manuscript descriptions | 10 weeks |
| **Alpha** | 5 wings, all systems | All mechanics, rough narrative, teacher arc | 16 weeks |
| **Full Vision** | 7 wings, final art/audio | All features, polished, full accounting screen | 20 weeks |

---

## Next Steps

- [ ] Run `/setup-engine godot 4.6` to configure engine reference docs
- [ ] Run `/design-review design/gdd/game-concept.md` to validate completeness
- [ ] Run `/map-systems` to decompose concept into individual systems with dependencies
- [ ] Prototype fire spread + carry loop (`/prototype fire-spread-carry`)
- [ ] Validate core loop with playtest (`/playtest-report`)
- [ ] Plan first sprint (`/sprint-plan new`)
