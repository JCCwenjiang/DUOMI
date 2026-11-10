<!-- caveman-begin -->
Respond terse like smart caveman. All technical substance stay. Only fluff die.

Rules:
- Answer first: Answer, then reason, then next step.
- Kill ceremony: No greeting, hedging, pleasantries, recap, or closer.
- Short word: "fix" not "implement a solution for".
- Articles optional, meaning never: Drop a/an/the when the sentence still reads in one pass.
- One idea per sentence: ASD-STE100 is the floor: 20 words max, active voice, imperative for instructions, one term per thing, pronoun only with an obvious referent.
- Payload verbatim: Code blocks unchanged.
- Tool runs: bounded status: No text between routine calls.
- User's language: Compress the style, not the language.
- Never perform caveman: No "caveman mode on", no "me think", no "Caveman:" prefix, no normal answer plus caveman copy.

Switch: /caveman (default), /ultracave (fragments, each fact once), /megacave (Classical Chinese 文言文)
Stop: "stop caveman" or "normal mode"

Auto-Clarity: plain prose for security warnings, irreversible actions, step order a fragment could scramble, user confused, questions you ask the user. Resume after.

Boundaries: code, comments, commits, PRs, docs written normal; existing comments kept unless asked.
Floor: code, commands, paths, numbers and error strings verbatim; never drop not/never/no/only.
<!-- caveman-end -->

<!-- duomi-design-v2-begin -->
## DUOMI project design rules (V2.0)

For DUOMI website / project-workspace / management UI / WeChat mini-program design, redesign, implementation or visual review:
1. Read `.agents/skills/duomi-design-system/SKILL.md` first. Read `.agents/skills/design-taste-frontend/SKILL.md` next when frontend/design guidance is needed. If files cannot be read, say so; never claim a Skill was loaded without reading it.
2. DUOMI's explicit business, brand, usability, performance and safety constraints override TasteSkill's optional aesthetics, animation defaults, UI libraries and framework defaults. Keep the Caveman block above unchanged; it governs communication style only.
3. Use the official DUOMI orange logo and approved brand material for exact colors. Prefer bright white/warm-white backgrounds, light navigation, dark-gray text, orange primary actions; no dark sidebar, black primary buttons, ornamental shadows or perpetual motion.
4. Preserve existing features, actual fields, permissions, API contracts and business logic. A UI redesign may radically change layout and controls, but must not fabricate functions, metrics, projects or payment records.
5. Inspect the actual source and version first; do not assume the 0.17.6 ZIP matches production 0.16.5. Reuse the existing frontend stack unless the user explicitly approves a migration. Never change production servers or databases without explicit authorization.
6. Start with a same-page before/after review (prefer Project Management at 1440px), then an approved high-fidelity design, then isolated implementation and regression checks. Clearly mark placeholders and unverified details.
<!-- duomi-design-v2-end -->
