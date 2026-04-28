# 📈 SEO & Content Marketing Skills Suite
### Derived from [alirezarezvani/claude-code-skill-factory](https://github.com/alirezarezvani/claude-code-skill-factory)

![Domain](https://img.shields.io/badge/Domain-SEO%20&%20Content%20Marketing-brightgreen?style=for-the-badge)
![Commands](https://img.shields.io/badge/Commands-10-blue?style=for-the-badge)
![Workflows](https://img.shields.io/badge/Workflows-5-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> **Adaptation of `alirezarezvani/claude-code-skill-factory` for SEO & Content Marketing use cases.**
> Source focus: _skill scaffolding, code agents, slash command generation_

---

## What This Skill Suite Does

Keyword research, content audits, SERP analysis, technical SEO and content strategy.

This collection provides **10 specialised commands** and
**5 multi-step workflows**, all with a consistent
structured-output UI so you always know exactly where you are and what to do next.

---

## Quick Install

```bash
# Clone this skill
cp -r . ~/.claude/skills/r00-alirezarezvani-claude-code-skill-factory--seo/

# Register in Claude Code
# In a Claude Code session:
/read ~/.claude/skills/r00-alirezarezvani-claude-code-skill-factory--seo/SKILL.md
```

---

## Commands

| Command | Description |
|---------|-------------|
| `/keyword-research` | Deep keyword clustering and opportunity scoring with SERP intent mapping |
| `/content-audit` | Full-site content quality score, duplication check and cannibalization report |
| `/technical-seo` | Crawl budget, Core Web Vitals, schema markup and indexability audit |
| `/competitor-gap` | Backlink gap, topic gap and featured-snippet opportunity analysis |
| `/content-brief` | AI-generated SEO content brief with outline, NLP terms and word count targets |
| `/serp-monitor` | Daily rank tracking report with volatility alerts and CTR optimisation tips |
| `/link-prospecting` | Quality backlink prospect list with DA/DR filters and outreach templates |
| `/page-speed-seo` | Render-blocking, LCP, CLS, FID diagnosis mapped to ranking impact |
| `/local-seo` | NAP consistency, Google Business Profile optimisation and local citation audit |
| `/content-calendar` | Data-driven editorial calendar built from search demand and seasonality |

**Usage:**
```bash
/keyword-research <target>
/content-audit --scope full --output md
```

---

## Workflows (Multi-step)

| Workflow | Description |
|----------|-------------|
| `full-seo-sprint` | 12-step SEO sprint: audit → keyword map → content plan → technical fixes |
| `launch-seo` | Pre-launch SEO checklist with canonical, hreflang and sitemap validation |
| `content-refresh` | Identify and refresh underperforming pages to recover lost rankings |
| `authority-building` | End-to-end digital PR and link-building campaign workflow |
| `ai-content-pipeline` | Keyword → brief → draft → optimise → publish automation pipeline |

**Usage:**
```bash
/workflows:full-seo-sprint <target> --scope full
```

---

## UI Design

All commands display structured output with:

- **Progress panels** — real-time step tracking
- **Findings tables** — sorted by severity (🔴🟠🟡🟢)
- **Action checklists** — quick wins → medium-term → strategic
- **Summary cards** — at-a-glance metrics after each command


## Progress Display Example

```
╔══════════════════════════════════════════════════╗
║  SEO Audit  —  domain.com                        ║
╠══════════════════════════════════════════════════╣
║  Crawling pages …      [████████░░]  80%  1 204/1 505  ║
║  Checking backlinks …  [███░░░░░░░]  30%    943/3 147  ║
║  Scoring content …     [██████████] 100%    Done ✓     ║
╚══════════════════════════════════════════════════╝

┌─────────────────────┬──────────┬──────────┬──────────┐
│ Metric              │ Current  │ Target   │ Status   │
├─────────────────────┼──────────┼──────────┼──────────┤
│ Crawlable pages     │    1 204 │    1 505 │  ⚠ 80 %  │
│ Pages w/ title tag  │    1 180 │    1 204 │  ✓ 98 %  │
│ Pages w/ meta desc  │      902 │    1 204 │  ✗ 75 %  │
│ Core Web Vitals     │     Good │     Good │  ✓ Pass  │
│ Mobile-friendly     │       97 │      100 │  ⚠ 97 %  │
└─────────────────────┴──────────┴──────────┴──────────┘
```


---

## Interaction Pattern

Every command follows this 5-step structure:

```
① Scope Confirmation  — verify target and options with user
② Live Analysis       — progress bar while working
③ Findings Table      — structured results sorted by impact
④ Action Plan         — prioritised, time-boxed recommendations
⑤ Next Steps          — suggested follow-up commands
```

---

## Source Repository

This suite is derived from
**[alirezarezvani/claude-code-skill-factory](https://github.com/alirezarezvani/claude-code-skill-factory)**
which focuses on: _skill scaffolding, code agents, slash command generation_.

Improvements in this adaptation:
- Domain-specific command vocabulary for SEO & Content Marketing
- Enhanced structured output with visual progress tracking
- Prioritised action plans with time estimates
- Workflow orchestration for end-to-end processes
- Consistent UI conventions across all commands

---

## License

MIT — free to use, modify and distribute.
