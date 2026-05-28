# hmu.sh Product Design v0.2

## 1. Product Positioning

**hmu.sh is intent-based social for personal AI agents.**

Core line:

> Social, routed by intent.

Plain-language version:

> Let people hit up your agent first.

hmu.sh gives every person a public social entry point, such as `hmu.sh/jerry`. Instead of sending a low-context DM, visitors first talk to the person's agent. The agent understands intent, gathers context, filters noise, and turns the request into a clear card the owner can act on.

This is not another feed-based social network. It is a personal agent social inbox.

## 2. Why Now

Current social tools are built around attention, not intent:

- DMs are noisy and unstructured.
- Contact forms feel cold and static.
- Calendar links expose time before fit is established.
- LinkedIn and X optimize for reach, not high-quality next steps.
- Personal agents are emerging, but they do not yet have a social protocol.

hmu.sh sits at the moment where personal AI agents need a public interface for contact, filtering, and routing.

## 3. Target Users

The first users should be people who receive more inbound requests than they can comfortably process:

- AI builders
- Indie hackers
- Founders
- Creators
- Investors
- Recruiters
- Freelancers and consultants
- Community operators

Their shared pain is not "I need more messages." It is "I need fewer low-quality interruptions and better context for the good ones."

## 4. User Promise

For the profile owner:

> Stop triaging vague DMs. Let your agent collect intent, context, and recommended next steps.

For the visitor:

> Make a better first contact. Explain why you are reaching out and get routed to the right next step.

For the network:

> Relationships become more useful when agents understand why people want to connect.

## 5. Core Product Loop

1. A user creates a public hmu.sh profile.
2. The user configures what they are open to.
3. A visitor lands on `hmu.sh/{username}`.
4. The visitor chooses an intent.
5. The agent asks a few context-gathering questions.
6. hmu.sh generates an intent card.
7. The profile owner accepts, declines, replies, schedules, asks for more context, or archives.
8. hmu.sh learns from those decisions and improves routing.

## 6. Intent Types

Initial intent taxonomy:

- Collaborate
- Ask for advice
- Hire me
- Get hired
- Invest / fundraise
- Invite me
- Make an intro
- Schedule a call
- Share something
- Just say hi

The taxonomy should remain editable. The owner should be able to add custom intents such as "Podcast guest", "Open-source maintainer request", "Angel deal", or "Design critique".

## 7. MVP Scope

The MVP should prove one loop:

> Public page -> AI intake -> intent card -> owner decision.

Included:

- Public profile page
- Owner profile setup
- Contact preferences
- Visitor intent selection
- AI intake chat
- Intent summary card
- Private inbox
- Basic actions: accept, decline, reply, ask for more context, archive
- Email notification for new high-quality requests

Deferred:

- Feed
- Follow graph
- Public posting
- Full agent-to-agent negotiation
- Marketplace matching
- Payments
- Multi-user organizations

## 8. Public Profile Experience

The profile should answer three questions quickly:

1. Who is this person?
2. What are they open to?
3. Which intent should I choose?

Example profile structure:

- Name, handle, short bio
- Current focus
- Open to
- Not open to
- Intent buttons
- Agent chat area

Tone should feel direct, quiet, and high-context. The page is not a creator Linktree clone; it is an intelligent social front door.

## 9. Agent Intake Behavior

The agent should not pretend to be the person. It should clearly act as the person's routing layer.

Good agent behavior:

- Ask only the questions needed for the selected intent.
- Prefer structured answers where possible.
- Ask one follow-up when context is missing.
- Summarize before submission.
- Respect the owner's boundaries.
- Make the visitor feel helped, not screened by a wall.

Example questions:

- What are you hoping to discuss?
- Why is this relevant to Jerry right now?
- What should the next step be if there is a fit?
- What background should Jerry know about you?
- Is there a specific deadline or timing constraint?

## 10. Intent Card

Each submitted request becomes an intent card:

- Visitor name
- Visitor role or background
- Selected intent
- One-sentence summary
- Why this matters
- Suggested next action
- Confidence / priority
- Key links
- Conversation transcript

Priority labels:

- High fit
- Needs review
- Needs more context
- Low fit
- Auto-decline candidate

## 11. Owner Inbox

The inbox should feel closer to a decision queue than a chat app.

Primary actions:

- Accept
- Reply
- Ask for more context
- Schedule
- Intro
- Decline
- Archive

The inbox should optimize for fast triage. The owner should be able to process many requests without opening long threads.

## 12. Differentiation

Compared with DM:

- More context before interruption
- Better filtering
- More actionable summaries

Compared with contact forms:

- Conversational
- Adaptive
- Better for ambiguous social requests

Compared with Calendly:

- Fit before time
- Different routing for different intents
- No open calendar link for everyone

Compared with LinkedIn / X:

- No feed
- No attention game
- Intent-first relationship building

## 13. Landing Page Narrative

Homepage hierarchy:

1. `Social, routed by intent.`
2. `Let people hit up your agent first.`
3. Explain public profiles like `hmu.sh/jerry`.
4. Show the flow: choose intent -> agent intake -> summarized card -> owner action.
5. Position as the social inbox for the agent era.
6. Early-access CTA.

Recommended homepage copy:

- H1: `Social, routed by intent.`
- Subhead: `hmu.sh lets people hit up your personal agent first, so every request arrives with context, fit, and a recommended next step.`
- CTA: `Request early access`
- Secondary CTA: `See how it works`

## 14. Brand Notes

Name:

- `hmu` means "hit me up".
- `.sh` suggests shell, command, agent, and developer culture.

Voice:

- Smart but not cute
- Direct but not cold
- Agent-native but human-centered
- Social without the feed

Design direction:

- Premium AI utility
- High signal, low noise
- Quiet interface density
- Intent cards, routing lines, profile nodes
- Avoid generic chatbot visuals

## 15. Roadmap

Phase 1: Landing page and waitlist

- Publish positioning
- Collect early users
- Validate ICP and use cases

Phase 2: Single-player inbox

- Public profiles
- Intent intake
- Card summaries
- Manual owner decisions

Phase 3: Personal agent memory

- Owner preferences
- Learned routing
- Reusable response patterns
- Calendar and email integrations

Phase 4: Agent-to-agent social

- Visitor agent can speak to owner agent
- Mutual fit summaries
- Automated intro proposals
- Lightweight trust signals

Phase 5: Intent social graph

- Discovery by current intent
- Warm intro paths
- Group and event routing
- Reputation for high-quality requests

## 16. Success Metrics

Landing page:

- Early-access conversion rate
- Handle reservation count
- ICP quality of signups
- Qualitative feedback from AI builders / founders

MVP:

- Requests submitted per profile
- Request completion rate
- Owner accept / decline ratio
- Time saved per inbox session
- Percentage of requests needing no follow-up clarification
- Repeat use by profile owners

## 17. Open Questions

- Should early profiles be invite-only?
- Should hmu.sh start with founder / AI builder positioning only?
- Should visitors need accounts, or can they submit as guests?
- Should the first AI intake be one-shot form plus follow-up, or full chat?
- Should early-access users reserve handles before product login exists?
- What is the first integration: email, calendar, X, LinkedIn, or GitHub?

