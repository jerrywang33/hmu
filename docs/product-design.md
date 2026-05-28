# hmu.sh Product Design v0.3

## 1. Product Positioning

**hmu.sh is a calm social intelligence layer for personal AI agents.**

Core line:

> AI that lowers social friction.

Public-facing line:

> Social intelligence for personal agents.

hmu.sh helps people and their agents clarify the hidden dynamics of a connection before a direct conversation begins. The product is not only an AI intake form and not simply an agent that chats on your behalf. Its deeper job is to make first contact healthier, clearer, and easier to act on.

The four product variables are:

- Pace
- Boundaries
- Reciprocity
- Expectations

Internal definition:

> hmu.sh helps personal agents manage pace, boundaries, reciprocity, and expectations before people connect.

## 2. Why This Matters

The hard part of social connection is often not writing a message. It is reading the situation.

People hesitate because they do not know:

- How fast to move
- Whether the ask is appropriate
- How to reject or redirect without awkwardness
- Whether the exchange is mutual
- What the next step should be
- Whether the other person expects a call, a favor, an intro, a reply, or a relationship

Existing tools do not solve this well:

- DMs are noisy and low-context.
- Contact forms are static and cold.
- Calendar links expose time before fit is clear.
- Social networks optimize attention instead of connection quality.
- AI agents can talk, but they usually do not understand relationship dynamics.

hmu.sh is designed around connection quality rather than message volume.

## 3. Core Product Model

Connection quality can be modeled as:

> Intent clarity + Context + Trust + Timing + Boundary fit + Mutual value + Expectation alignment

hmu.sh improves these inputs before the owner has to spend attention.

The agent should answer:

- Why is this person reaching out?
- Why now?
- What do they want next?
- Is this request within the owner's boundaries?
- Is there value for both sides?
- Should this move quickly, slowly, async, or not at all?

## 4. The Four Variables

### Pace

Social connection is not always better when it moves faster.

The agent should help decide:

- Reply now
- Ask for more context
- Move async first
- Schedule a short call
- Slow down
- Park for later
- Decline

Product signals:

- Suggested pace
- Timing clarity
- Urgency quality
- Recommended next step

### Boundaries

Boundaries make social life sustainable. The product should help owners express preferences without seeming cold or unavailable.

The agent should help:

- Define what the owner is open to
- Redirect requests outside the owner's scope
- Decline gently
- Protect time and attention
- Ask for missing context before allowing escalation

Product signals:

- Boundary fit
- Outside scope
- Needs context
- Allowed next steps

### Reciprocity

High-quality outreach is not purely extractive. The agent should help both sides see whether there is mutual value.

The agent should ask:

- What makes this useful for both people?
- What does the visitor bring?
- Why would the owner care?
- Is this mostly an ask, or is there a real exchange?

Product signals:

- Balanced
- Mostly ask
- Strong mutual value
- Reciprocity unclear

### Expectations

Many social failures come from misaligned expectations.

The agent should clarify:

- Does the visitor want a reply, a call, an intro, advice, hiring, collaboration, or emotional support?
- Is the requested next step reasonable?
- Does the owner prefer async-first?
- Does success mean a meeting, a yes/no answer, a referral, or simply being seen?

Product signals:

- Expected next step
- Expectation match
- Mismatch warning
- Suggested reframing

## 5. Product Shape

The first product is still a public personal entry point:

`hmu.sh/{handle}`

But the page should not feel like a profile page, link-in-bio, or chatbot.

It should feel like:

> A first contact protocol.

Each owner has:

- Public identity
- Current focus
- Open-to list
- Not-open-to list
- Contact preferences
- Agent intake behavior
- Inbox of relationship dynamics cards

## 6. Core Loop

1. The owner creates a public hmu.sh profile.
2. The owner configures boundaries, preferred pace, and accepted intents.
3. A visitor lands on the profile.
4. The visitor chooses why they are reaching out.
5. The agent asks targeted questions about intent, timing, mutual value, and next step.
6. hmu.sh generates a relationship dynamics card.
7. The owner chooses: reply, ask more, schedule, intro, decline, archive, or save for later.
8. hmu.sh learns from owner decisions and improves future routing.

## 7. Relationship Dynamics Card

The card is the core artifact.

It should include:

- Visitor
- Intent
- Summary
- Why now
- Why this person
- Suggested next step
- Pace
- Boundary fit
- Reciprocity signal
- Expectation alignment
- Links and context
- Transcript when needed

Example:

```text
Intent: Collaborate
Pace: Async first, then 15-min call
Boundary fit: Within current AI social focus
Reciprocity: Strong mutual learning value
Expectation: Wants a pilot conversation
Suggested move: Ask for pilot criteria before scheduling
```

This is the product's differentiation from a normal AI inbox. The card does not only summarize a message. It reads the social situation.

## 8. Agent Behavior

The agent should not pretend to be the owner. It should act as the owner's social routing layer.

Good behavior:

- Ask only questions that improve connection quality.
- Avoid interrogating the visitor.
- Make boundaries feel human.
- Reduce awkwardness for both sides.
- Suggest gentle next steps.
- Prefer clear structure over long chat.
- Never promise access to the owner without permission.

Bad behavior:

- Manipulative persuasion
- PUA-style tactics
- Fake intimacy
- Over-automation
- Pretending to know the owner's feelings
- Pushing every request toward a call

## 9. MVP Scope

The MVP should prove one loop:

> Public page -> AI intake -> relationship dynamics card -> owner decision.

Included:

- Public profile page
- Owner preferences
- Visitor intent selection
- AI intake
- Relationship dynamics card
- Private inbox
- Basic actions: reply, ask more, schedule, decline, archive
- Email notification for high-quality requests

Deferred:

- Feed
- Follow graph
- Dating-specific workflows
- Fully automated agent-to-agent negotiation
- Marketplace matching
- Payments
- Organization accounts

## 10. First ICP

Start with people who receive valuable but noisy inbound:

- AI builders
- Founders
- Creators
- Investors
- Community operators
- Freelancers and consultants

The first narrative should focus on AI builders and founders because they understand personal agents and have immediate inbound triage pain.

## 11. Brand Notes

Name:

- `hmu` means "hit me up".
- `.sh` suggests shell, command, agent, and builder culture.

Voice:

- Calm
- Clear
- Human
- Socially intelligent
- Agent-native without sounding robotic

Avoid:

- PUA language
- Overclaiming neuroscience
- Dark AI aesthetics
- Feed-based social language
- "AI replaces your relationships"

Design direction:

- Fresh, light, and quiet
- More Headspace / Paired than dark AI dashboard
- Soft green, pale blue, warm white, graphite
- Lightweight cards and signals
- Plenty of whitespace
- The feeling of lower social pressure

## 12. Landing Page Narrative

Homepage hierarchy:

1. `AI that lowers social friction.`
2. Explain that hmu.sh helps agents clarify pace, boundaries, reciprocity, and expectations.
3. Show the four variables.
4. Show the relationship dynamics card.
5. Explain the first contact protocol.
6. Invite early access.

Recommended homepage copy:

- H1: `AI that lowers social friction.`
- Subhead: `hmu.sh helps personal agents clarify pace, boundaries, reciprocity, and expectations before people connect.`
- CTA: `Request early access`
- Secondary CTA: `Explore the model`

## 13. Roadmap

Phase 1: Landing page and waitlist

- Publish the new positioning
- Collect early users
- Validate whether the four-variable model resonates

Phase 2: Single-player social intelligence inbox

- Public profiles
- AI intake
- Relationship dynamics cards
- Manual owner decisions

Phase 3: Learned social preferences

- Boundary memory
- Pace preferences
- Reusable response patterns
- Calendar and email integrations

Phase 4: Agent-to-agent connection

- Visitor agents can speak with owner agents
- Mutual-fit summaries
- Automated intro proposals
- Trust and reputation signals

Phase 5: Intent social graph

- Discovery by current intent
- Warm intro paths
- Relationship quality signals
- Social without the feed

## 14. Success Metrics

Landing page:

- Early-access conversion rate
- Quality of signup intent
- Handle reservation demand
- Qualitative resonance around pace / boundaries / reciprocity / expectations

MVP:

- Submitted requests per profile
- Owner accept / decline / ask-more ratio
- Requests needing no extra clarification
- Time saved per inbox session
- Owner trust in suggested next steps
- Repeat use by profile owners

## 15. Open Questions

- Should the first intake be chat-like, form-like, or a hybrid?
- Which four-variable labels should be visible to visitors versus owner-only?
- Should visitors see boundary feedback before submitting?
- Should agent intake ever coach visitors to rewrite their outreach?
- Should hmu.sh support personal/dating contexts later, or stay professional-social first?
- What is the first integration: email, calendar, X, LinkedIn, or GitHub?
