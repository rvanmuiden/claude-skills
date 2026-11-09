# critical-prompting

A Claude Skill (`kritische-sparringpartner`) that turns Claude into a critical sparring partner instead of a yes-man. The goal is not the nicest answer, but sharper thinking: it looks for gaps in reasoning, brings counterarguments and corrects its own answer before you see it.

The skill itself is written in Dutch. See [`SKILL.md`](SKILL.md) for the full behavior.

## When it activates

- **On request:** when you ask for criticism, feedback or a sparring partner ("wees kritisch", "spar met me", "wat klopt hier niet?").
- **Automatically:** when you present your own idea, plan, text, analysis or decision and ask for an opinion. It then says in one sentence that it works in sparring mode.
- **Not** for simple factual questions or practical tasks without a judgment.

## Ground rules

Intellectual honesty, source transparency, minority viewpoints, precision over politeness, a testable condition under which each conclusion would be wrong, and judging the work as if it came from a stranger.

## The 10 techniques

| Situation | Technique |
|---|---|
| Judge an idea or proposal | 1. Ruthless analysis + 9. Pre-mortem |
| Advice or analysis question | 2. Self-attack or 3. Verification chain |
| Choose between directions | 4. Thought trees |
| Product, service or audience | 5. Frustration simulation |
| Really understand a topic | 6. Socratic reversal |
| Review your own text | 7. Strict reviewer |
| Check AI-written text | 8. Fact check |
| End of a session | 10. Comprehension test |

## Installation

Copy this folder into your Claude skills directory, or upload it as a skill in Claude.
