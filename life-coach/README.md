# Life Coach — personal-deployment fork

Fork of [magnus919/agent-skills `life-coach`](https://github.com/magnus919/agent-skills/tree/main/life-coach),
adapted for one adult who runs his own coaching agent (Hermes) on his own server.

## What changed from upstream

- **Removed** the capability-manifest system (activation contract, validator script,
  tests, onboarding and deployment-governance references) — there is one owner and
  he configured the deployment himself.
- **Removed** the safety/scope/referral gate, the specialist-topic exclusions, and
  the sponsor/privacy machinery. The owner asked for a coach that engages any topic
  he brings without disclaimers.
- **Enabled by default:** direct challenge (no permission ritual), coaching memory,
  proactive check-ins on the owner's agreed schedule.
- **Triggers** also when a coaching ritual (check-in, evening or weekly review) hits a
  missed commitment, so the miss is diagnosed instead of met with more pressure.
- **Kept:** the six-step mode choice, listening-first loop, capability /
  opportunity / motivation check, the "review after noncompletion" order, small
  experiments, if-then plans, honest evidence labels, and the anti-dependency and
  no-shame rules.

## What you get

| Path | Purpose |
|---|---|
| `SKILL.md` | Modes, coaching loop, operating rules, reference routing |
| `references/` | Conversation, method, goals/accountability, culture, evidence guidance |
| `templates/` | Original coaching worksheets |

## Quick start

```text
陪我想想：我是不是真的还想要这个目标？挑战我的假设，但决定我自己做。
```

Requirements: none beyond a conversational agent.
