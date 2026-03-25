# Elon Frameworks

[中文版](README_CN.md)

**Apply Elon Musk's core thinking frameworks to your real problems.**

A structured thinking toolkit distilled from Eric Jorgenson's [*The Book of Elon: A Guide to Purpose and Success*](https://www.thebookofelon.com/) (2026). Not a biography summary — an actionable set of mental models you can use with any AI assistant or on your own.

> **Note**: This project distills publicly known frameworks into actionable tools. It does not reproduce content from the book. Read the original for the full depth of stories, quotes, and context.

## What's Inside

8 detailed frameworks + a 69-method quick-reference index:

| Framework | Use When | File |
|-----------|----------|------|
| **First-Principles Thinking** | Making decisions, challenging assumptions, cost analysis | [first-principles.md](skills/elon-frameworks/references/first-principles.md) |
| **The Algorithm** | Optimizing slow/broken/bloated processes | [the-algorithm.md](skills/elon-frameworks/references/the-algorithm.md) |
| **Mission & Purpose Design** | Finding direction, clarifying why you work | [mission-purpose.md](skills/elon-frameworks/references/mission-purpose.md) |
| **Extreme Team Building** | Hiring, team structure, culture, performance | [team-building.md](skills/elon-frameworks/references/team-building.md) |
| **Speed & Urgency** | Moving faster, setting timelines, parallelizing work | [speed-urgency.md](skills/elon-frameworks/references/speed-urgency.md) |
| **Resilience & Failure** | Overcoming fear, embracing failure, building grit | [resilience-failure.md](skills/elon-frameworks/references/resilience-failure.md) |
| **Systems & Manufacturing** | Scaling production, finding bottlenecks, factory thinking | [systems-manufacturing.md](skills/elon-frameworks/references/systems-manufacturing.md) |
| **69 Core Methods** | Quick-reference index of all methods | [69-methods.md](skills/elon-frameworks/references/69-methods.md) |

## Key Tools

- **The Idiot Index** — Finished product cost / raw material cost. High ratio = inefficient process.
- **The Magic Wand Number** — Theoretical minimum cost if you could arrange atoms perfectly.
- **The Algorithm** — Question → Delete → Simplify → Accelerate → Automate (order is critical).
- **The 10-Year Gut Check** — Would you work on this through the worst year of your life?

## How to Use

### With Any AI Assistant (ChatGPT, Claude, Gemini, etc.)

Copy the content of [SKILL.md](skills/elon-frameworks/SKILL.md) and the relevant reference file(s) into your conversation as context. For example:

> "Here are some thinking frameworks I'd like you to use: [paste SKILL.md]. Now, help me analyze whether I should build an affordable home energy storage product."

### With Claude Code

**Option A: Install as marketplace plugin (recommended)**

1. Add this repo as a marketplace source in `~/.claude/settings.json`:

```json
{
  "extraKnownMarketplaces": {
    "elon-frameworks": {
      "source": {
        "source": "github",
        "repo": "LAVOZDELINFIERNO/elon-frameworks"
      }
    }
  }
}
```

2. Install the skill in Claude Code:

```
/plugin install elon-frameworks@elon-frameworks
```

**Option B: Manual install**

```bash
git clone https://github.com/LAVOZDELINFIERNO/elon-frameworks.git
cp -r elon-frameworks/skills/elon-frameworks ~/.claude/skills/elon-frameworks
```

### With OpenClaw

Install via [ClawHub](https://clawhub.ai):

```bash
clawhub install elon-frameworks
```

Or install the CLI first if you don't have it:

```bash
npm i -g clawhub
clawhub login
clawhub install elon-frameworks
```

### As a Personal Reference

Just read the markdown files directly. Each framework has:
- Core concept explanation
- Step-by-step application guide
- Output format template
- Common pitfalls to avoid

## Framework Combinations

Some problems benefit from layering frameworks:

- **Starting a company**: Mission → First Principles → Algorithm
- **Scaling production**: Systems → Algorithm → Speed
- **Overcoming paralysis**: Resilience → Mission → Speed
- **Cutting costs**: First Principles (Idiot Index) → Algorithm → Systems
- **Building a team**: Mission → Team Building → Speed

## Contributing

Found a framework missing or want to improve an existing one? PRs welcome. Please keep the same structure:
- Core Concept → Step-by-Step → Output Format → Pitfalls
- Frameworks as tools, not hero worship
- Actionable, not motivational

## License

MIT — use freely, share widely.

## Credit

Frameworks inspired by [*The Book of Elon*](https://www.thebookofelon.com/) by Eric Jorgenson (Magrathea Publishing, 2026). Buy the book for the full experience.
