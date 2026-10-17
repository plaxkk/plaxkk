<h1 align="center">plaxkk</h1>

<p align="center">
  Building AI workflows for reading, writing, and everyday life — and a world to explore.
</p>

<p align="center">
  <a href="https://github.com/plaxkk?tab=repositories">Projects</a>
  · <a href="https://paper-loop-xi.vercel.app/">Read Paper Loop</a>
  · <a href="https://github.com/plaxkk/persona-studio">Persona Studio</a>
  · <a href="https://mirrorlife.kkplayit.online/">Play MirrorLife</a>
</p>

---

**Be real, be brave, be positive.**

I build small products around problems I want to understand: learning from AI papers, finding a personal writing voice, working with coding agents, creating living game worlds, coordinating family life, and planning trips. I use these projects to explore what one person can build with AI while keeping product decisions and review in human hands.

## What I've Been Building in 2026

Work through **October 17, 2026**. The latest changes since September 19 are a live Paper Loop reading site, a new Persona Studio for X content, a rebuilt Nestful data layer and daily-use interface, and continued work on MirrorLife's playable 3D interiors.

| Theme | Project | Explore |
| --- | --- | --- |
| Research and writing | **Paper Loop** — a classic-paper timeline, PDF reading workspace, and writing toolchain | [Read](https://paper-loop-xi.vercel.app/) · [Source](https://github.com/plaxkk/paper-loop) |
| Personal content workflows | **Persona Studio** — writing voice, draft editing, interaction review, and analytics for X | [Source](https://github.com/plaxkk/persona-studio) |
| Social simulation | **MirrorLife** — relationships, memories, and a playable 3D community experiment | [Play](https://mirrorlife.kkplayit.online/) · [Source](https://github.com/plaxkk/MirrorLife) |
| Family collaboration | **Nestful** — shared routines, reminders, and memories in a WeChat Mini Program preview | [Source](https://github.com/plaxkk/nestful) |
| Itinerary planning | **TravelAi** — conversational planning, daily itineraries, and maps | In development · private source |
| AI development workflows | **AiTeam** — local project visibility, execution review, and rule feedback | [Source](https://github.com/plaxkk/AiTeam) |
| Browser utilities | **jetbrains-keygen** — a browser-based technical research tool | [Website](https://jetbrains-keygen.kkplayit.online/) · [Source](https://github.com/plaxkk/jetbrains-keygen) |

### Paper Loop · From Reading a Paper to Writing About It

Paper Loop now has a public reading site alongside its original research-and-writing tools. A chronological route through classic AI papers connects Chinese explanations, formulas, figures, and related reading. The October update brought 12 of my previously published WeChat essays and their original illustrations into the site; the DPO entry remains an editorial draft.

The reading workspace supports PDF uploads, arXiv imports, page navigation, reading-progress recovery, and deletion. It runs on Vercel with Supabase persistence and private PDF storage. Translation and cited Q&A are implemented but currently disabled on the hosted site while AI is turned off.

The original Python toolchain still covers paper study, writing preferences, source-based review, formula and figure handling, multi-platform drafts for human review, and feedback for the next article.

[Read Paper Loop](https://paper-loop-xi.vercel.app/) · [Source](https://github.com/plaxkk/paper-loop)

### Persona Studio · Developing a Writing Voice With AI

Persona Studio is a personal X content workspace adapted from [Another-Person-in-X](https://github.com/NoMTF/Another-Person-in-X). It brings a configurable persona, ideas from my Git and coding-session records, draft conversations, editing, and an interaction inbox into one workflow. Writing engines include Codex, Claude Code, OpenClaw, and Hermes.

Since September, it has grown into a local agent with a hosted panel and an authorized browser connector. Recent work adds account analytics, weekly reviews, persona version comparison, and a staged growth plan. Follower observations show the sample coverage and collection time; experiments still need enough real data before drawing conclusions.

I review and edit the drafts, then copy them to X and complete publication myself. The current workspace keeps posting and account actions in human hands.

[Explore Persona Studio](https://github.com/plaxkk/persona-studio)

### MirrorLife · Trying Another Life Through a Simulated World

MirrorLife is an experimental social-simulation and narrative game. Create an avatar, explore a community, and see how actions shape relationships, memories, and later stories.

Recent development centers on a two-story shared atrium: third-person exploration, two stair routes, discoverable objects, resident conversations, and a shared decision that feeds back into the world. Work since September includes character clothing and hand studies, dialogue framing, walk-cycle fixes, rendering, and repeatable asset-export tooling.

The exploration → conversation → decision loop has been exercised in development builds. Final character art and desktop performance targets remain unfinished, and the latest local experiments are not all part of the public demo.

[Play MirrorLife](https://mirrorlife.kkplayit.online/) · [Source](https://github.com/plaxkk/MirrorLife)

### Nestful · A Shared Home for Family Routines

Nestful is a WeChat Mini Program for family coordination and shared memories. Its core flows cover family spaces, invitations, activities and preparation tasks, birthday and health reminders, shared records, memories, and a household ledger.

October's work moved the backend from shared application state to a relational PostgreSQL model on Supabase, with family isolation and concurrency checks. The interface now centers on one primary family, today's tasks, and the next seven days, with direct reminder access, simpler navigation, consistent visuals, and fewer sequential startup requests.

The backend is deployed; the Mini Program remains a preview. Two-account invitation checks and actual WeChat notification delivery still need device acceptance before a formal release.

[Explore Nestful](https://github.com/plaxkk/nestful)

### TravelAi · A Trip Plan You Can Keep Talking To

TravelAi's itinerary planner turns a destination, trip length, budget, and interests into an editable daily plan. Conversation, itinerary details, and an interactive map sit together, so travelers can refine a route while seeing how the days and places fit.

The project includes conversational revisions, itinerary saving, shareable plans that others can adapt, an in-trip AI assistant, multilingual interfaces, and mobile layouts. Recent supporting work has focused on content presentation, navigation, and consistent visual design.

I also built supporting skills for extracting evidence-backed travel needs from public videos, organizing source-backed guide material, reviewing editorial quality, and multilingual rewriting with factual-consistency checks.

The project is under active development; source code is private.

### AiTeam · Working With an AI Development Team

AiTeam grew out of a practical question: when coding agents are doing a lot of work, how do I tell whether a project is actually moving forward?

It collects local Codex and Claude Code sessions, groups them by repository, and turns execution records into project health, role evaluations, audit findings, and cost visibility. Founder briefs, execution reviews, and accepted lessons help feed clearer rules into the next iteration. Conversation data stays local by default.

[Explore AiTeam](https://github.com/plaxkk/AiTeam)

### jetbrains-keygen · A Small Browser Utility

A static, browser-based JetBrains activation-code generator for technical study. The page performs generation locally and provides product selection, configurable license details, and copyable output.

It includes usage documentation, Chinese, English, Korean, and Russian pages, and multilingual search indexing. It is an independent research project, unaffiliated with JetBrains.

[Website](https://jetbrains-keygen.kkplayit.online/) · [Source](https://github.com/plaxkk/jetbrains-keygen)

## How I Work

- Start with a concrete, usable flow and improve it through feedback.
- Keep private and personal data local where practical.
- Use AI agents heavily, with explicit scope, review, and delivery evidence.
- Turn recurring lessons into reusable project rules and skills.
- Be clear about what works today and what is still an experiment.

Project descriptions reflect repository documentation and development records reviewed for this update. Public source links are included where available. See [PROFILE_SOURCES.md](PROFILE_SOURCES.md) for the evidence and link-selection notes.

Last updated: **2026-10-17**.

---

<p align="center">
  <sub>Real work, clear limits, steady improvement.</sub>
</p>
