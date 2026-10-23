# My Copilot Framework

*A lightweight personal context framework for Microsoft 365 Copilot.*

**Version 1.0** · [MIT License](LICENSE)

## Give Microsoft 365 Copilot context that belongs to you

Microsoft 365 already contains much of your work: emails, meetings, chats, files and connected organisational information.

But it does not automatically know which priorities matter most to you, why you made an important decision, what you are learning, where a project is heading, or where you want your career to go.

**My Copilot Framework gives that context a home.**

> **Your Markdown files hold the memory.**  
> **Microsoft 365 holds the work.**  
> **Copilot does the reasoning.**  
> **The recommended My Copilot Framework Agent brings them together.**

## The product

My Copilot Framework is a portable, human-readable and AI-readable personal context layer for Microsoft 365 Copilot.

```text
YOUR WORK
Email · Teams · Meetings · Files · Connected systems
                         |
                         v
             MICROSOFT 365 COPILOT
            Search · Summarise · Reason
                         |
              +----------+----------+
              |                     |
              v                     v
       NORMAL COPILOT       MY COPILOT FRAMEWORK AGENT
         fallback                  recommended
              |                     |
              +----------+----------+
                         |
                         v
                 MY COPILOT FRAMEWORK
       Priorities · Projects · Decisions · Ideas
       Learning · Career direction · Reflection
```

## Recommended experience

Use the **My Copilot Framework Agent** as the front door.

The agent is recommended because it can hold reusable instructions, understand the role of each framework file, expose consistent workflows, and combine the configured work knowledge available in your Microsoft environment with your curated personal context.

The framework still works without an agent. The fallback experience is normal Microsoft 365 Copilot with relevant framework files attached or referenced when needed.

## Start here

1. Open `START-HERE/NEW-USER.md`.
2. Copy `INSTALL/starter-kit/` into an organisation-approved OneDrive location.
3. Complete the four-file foundation.
4. Create the recommended agent using `AGENT-RECOMMENDED/SETUP.md`.
5. Test it with `Start my day.`

Want to see it filled in first? Read `docs/EXAMPLE.md`.

## The four-file foundation

Start only with:

1. `01 Me.md`
2. CURRENT in `02 Current Focus.md`
3. `07 Career Vision.md`
4. `09 Personal Brand.md`

Add projects, decisions, ideas, reviews and learning as real work creates a reason to preserve them.

## Core workflows

```text
START      Start my day.
CONTINUE   Continue [project].
REMEMBER   Remember this in my framework.
EXPLORE    Explore this idea using my context.
REFLECT    Help me reflect on this week.
GROW       Help me grow using my direction and work.
CLOSE      Close my day and identify only what deserves preservation.
SYNC       Compare current understanding with my framework and propose updates.
```

## What belongs in your framework files?

Preserve meaning, not activity.

Good candidates:

- meaningful priorities;
- project direction and current state;
- confirmed decisions and rationale;
- ideas worth revisiting;
- outcomes and evidence;
- useful learning;
- career direction;
- how you want to contribute professionally.

Do not copy every email, meeting or Teams message. Microsoft 365 already contains work activity.

## Information architecture

```text
NOW
├── 01 Me.md
├── 02 Current Focus.md
└── 03 Projects/

MEMORY
├── 04 Decision Log.md
├── 05 Idea Backlog.md
└── 06 Weekly Reviews/

DIRECTION
├── 07 Career Vision.md
├── 08 Growth & Learning.md
└── 09 Personal Brand.md

OPTIONAL
└── 10 Optional/Feedback.md
```

## Maintenance

- **UPDATE:** Me, Career Vision, Personal Brand.
- **CURRENT + HISTORY:** Current Focus and Projects.
- **APPEND:** Decision Log, Idea Backlog, Weekly Reviews, Growth & Learning, optional Feedback.
- **ARCHIVE:** Completed or inactive material that no longer belongs in active context.

> **Stable files. Evolving content.**

## Memory model

- Microsoft 365 work sources are evidence and current activity.
- Copilot conversations are working sessions.
- My Copilot Framework files are the canonical curated personal memory.
- Agent outputs are proposals unless a write action is explicitly confirmed.

## Safe upgrades

> **The framework can change. Your history should not.**

Never copy blank templates from a newer version over your populated personal files. Any future version that changes the file structure will include a migration guide.

## Documentation map

- `START-HERE/NEW-USER.md` — full first-use journey.
- `START-HERE/DAILY-USE.md` — practical routines.
- `AGENT-RECOMMENDED/` — recommended agent setup, instructions and prompts.
- `FALLBACK-NO-AGENT/` — manual Copilot workflow.
- `INSTALL/starter-kit/` — personal context templates.
- `docs/EXAMPLE.md` — a worked example with a fictional user.
- `docs/` — architecture, design principles, maintenance, use cases and responsible use.
- `PRIVACY.md` — privacy guidance.
- `CONTRIBUTING.md` — how to contribute.
- `CHANGELOG.md` — version history.

## One sentence

**Microsoft 365 Copilot helps you understand your work. My Copilot Framework helps it understand what matters to you.**

## About

My Copilot Framework is an independent personal project by Peter Pesta. It is not affiliated with, endorsed by or sponsored by Microsoft. Microsoft, Microsoft 365 and Copilot are trademarks of the Microsoft group of companies.

## Licence

Released under the [MIT License](LICENSE).
