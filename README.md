# Hypercare Rollout Monitor

A concept tool for monitoring how a newly launched AI assistant is performing during its first weeks live with a client — built around EliseAI's AI Operations Specialist role.

**[View live demo →](https://gracy1305.github.io/hypercare-monitor/)**

## The problem

EliseAI's AI agents handle conversations for renters and patients across housing and healthcare. When a new client goes live, someone on the AI Operations team has to watch that rollout closely during "hypercare" — the first stretch of weeks where issues are most likely to surface.

EliseAI's own published research on affordable housing found that trust in AI drops sharply around compliance-sensitive topics — things like income recertification and program eligibility — where a wrong or overly generic answer can have real consequences, not just an annoying customer experience. And with EliseAI onboarding new clients quickly, manually reading every conversation to catch these moments doesn't scale.

## The idea

Instead of a generic analytics dashboard, this tool simulates what an AI Ops Specialist would actually need day to day:

- **A day-by-day health score** for each client's rollout, so you can see at a glance whether a client is trending fine or heading into trouble
- **Automatic flagging by risk type** — compliance-sensitive conversations, escalation patterns, repeated failures, and sentiment dips are treated differently, since a missed housing recertification question is not the same severity as a slow tour-booking link
- **A daily digest with real examples**, so the person reviewing it can see exactly what happened in a flagged conversation, not just a count

The goal was to build something that maps directly to the actual responsibilities in the role — monitoring AI performance, running hypercare on new clients, and surfacing recurring issues — rather than a generic "AI dashboard."

## Notes

This is an independent concept project built to explore how this kind of workflow could work, created as part of a job application to EliseAI. It uses simulated data throughout and is not affiliated with, endorsed by, or built using any internal EliseAI tools, data, or systems.

## Built with

Plain HTML, CSS, and JavaScript — no frameworks, no build step.
