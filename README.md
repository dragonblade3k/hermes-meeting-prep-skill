# hermes-meeting-prep-skill

A [Hermes Agent](https://github.com/NousResearch/hermes-agent) skill tap with one skill, **meeting-prep**: it turns an upcoming meeting into a short, read only brief (purpose, latest messages, open questions, what to bring, conflicts, flags) using whatever calendar, inbox and notes tools the agent has, and treats all email and calendar text as untrusted data.

Built for CSCI 599 (Agentic AI, USC), Assignment 3. No credentials, personal data or machine specific paths.

## Install

```bash
# as a tap
hermes skills tap add dragonblade3k/hermes-meeting-prep-skill
hermes skills install dragonblade3k/hermes-meeting-prep-skill/meeting-prep

# or directly, without adding the tap
hermes skills install dragonblade3k/hermes-meeting-prep-skill/skills/meeting-prep
```

Then ask your agent: "Prep me for my next meeting."

## Layout

```
skills/
  meeting-prep/
    SKILL.md
```

License: MIT
