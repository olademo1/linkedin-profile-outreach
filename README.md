# LinkedIn profile outreach

A portable version of Rotimi's profile-reading and initial-outreach writing guidance.

## What to transfer

The [linkedin-profile-outreach](linkedin-profile-outreach/) folder contains the skill. [SKILL.md](linkedin-profile-outreach/SKILL.md) holds all the instructions; `agents/openai.yaml` is optional interface metadata. There are no scripts, API keys, private candidate records, account connections, or other skill dependencies.

For an assistant that accepts instruction files, attach `SKILL.md` and ask it to follow the file. You can also copy its contents into the destination assistant's reusable instructions. For a system that supports skill folders, transfer the whole folder using that system's skill installation method.

## Starter prompt

```text
Follow the attached LinkedIn profile outreach skill.

Review the profile below, explain the strongest professional hook briefly, and draft one initial LinkedIn recruiting message.

Profile: [paste the profile text or attach readable screenshots]
Opportunity: [core work, level, and one or two confirmed selling points]
Location/work policy: [if known]
Sender: [your name; email only if you want it included]
Company name: [withhold by default, or explicitly ask to include it]
Message length or channel: [optional]
```

## Included

Evidence-based profile review, subtle professional hooks, recommendation and career-story interpretation, opportunity alignment, Rotimi's writing preferences, a final factual check, and a clearly fictional example.

## Left out

Paraform role navigation, requisition management, sourcing quotas, candidate saving, historical client-specific exclusions, project tracking, Call Brief sync, inbox reply handling, and sending messages.

The source was adapted from the existing Paraform outreach-personalization guidance and Rotimi's writing style. The original skills were not changed.
