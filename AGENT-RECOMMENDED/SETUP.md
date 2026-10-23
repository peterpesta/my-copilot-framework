# Agent Setup

## 1. Create the agent

In the Microsoft 365 Copilot app, open **Agents** and choose **Create agent** to use the agent builder. If you need more control, you can build the same agent in Microsoft Copilot Studio.

Name it `My Copilot Framework`.

Available options depend on your Microsoft 365 licence and your organisation's settings.

## 2. Add framework knowledge

Prefer a OneDrive or SharePoint knowledge connection that remains associated with the working framework files or folders where your environment supports that behaviour.

Recommended core framework sources:

- 01 Me.md
- 02 Current Focus.md
- 03 Projects/PROJECT INDEX.md
- active project files when useful
- 04 Decision Log.md
- 05 Idea Backlog.md
- current yearly Weekly Reviews file
- 07 Career Vision.md
- 08 Growth & Learning.md
- 09 Personal Brand.md
- optional Feedback.md

## 3. Add current-work knowledge where available

Add only the knowledge options suitable for the intended personal workflow and allowed by your organisation. Examples may include work email, Teams chats/meetings, SharePoint, websites and connector-provided knowledge.

## 4. Add instructions

Paste the block from `INSTRUCTIONS.md` into the agent instructions/behaviour area where supported.

## 5. Add starters

Use the prompts in `STARTER-PROMPTS.md` where conversation starters are supported.

## 6. Test source boundaries

Ask:

```text
List the configured knowledge categories you can actually use for this response. Do not infer unavailable sources.
```

Then:

```text
What do you know about my current focus from My Copilot Framework?
```

Finally:

```text
Start my day.
```

Verify that recorded context, current evidence and suggestions are clearly separated.
