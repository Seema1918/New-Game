# AI PM Portfolio Setup

This guide outlines how to plan and build a portfolio for AI Product Manager roles. It is a setup brief, not a completed portfolio website.

## Current State

The workspace currently contains two standalone browser-game projects: a memory game and Slide Shift. The portfolio site, personal career details, and portfolio case studies have not been provided or built yet. See [`context.md`](context.md) for the project brief, content guardrails, current repository inventory, and questions to resolve.

The root [`README.md`](README.md) remains the guide to the memory game. [`README_SLIDING_PUZZLE.md`](README_SLIDING_PUZZLE.md) documents Slide Shift. This file is intentionally separate so portfolio planning does not replace game documentation.

## Purpose

Build a concise, professional home for evidence of product-management work: how the owner finds meaningful problems, makes product decisions, collaborates across functions, delivers solutions, and measures outcomes. For AI-specific work, show why AI was appropriate and how quality, safety, cost, latency, user control, and ongoing evaluation were considered.

The portfolio should help a reviewer quickly answer:

- What kinds of product problems does this person work on?
- What did they personally own or influence?
- How did they make important decisions?
- What evidence shows the work made a difference?
- What did they learn and change as a result?

## Suggested Site Structure

- **Home**: factual positioning, a brief introduction, selected work, and clear links to resume and contact.
- **Case studies**: two or three substantial stories with clear role, context, decisions, delivery, outcomes, and learning.
- **AI work or experiments**: optional section for prototypes, evaluations, product teardowns, or personal projects. Label the type of work accurately.
- **About**: concise professional background and interests, based only on owner-provided facts.
- **Resume / Contact**: approved links and a straightforward way to get in touch.

Start with fewer, stronger examples. Add sections only when there is meaningful content for them.

## Case Study Template

Use this outline for each project and adapt it to the available evidence:

1. **One-line summary**: the user, problem, solution, and verified result.
2. **Context**: product, audience, business goal, constraints, timeline, and collaborators.
3. **My role**: decisions and responsibilities personally owned; work owned by others should be credited accurately.
4. **Problem evidence**: user research, support signals, usage data, or validated assumptions.
5. **Options and trade-offs**: paths considered, prioritization rationale, and what was deliberately not built.
6. **AI rationale**: the task AI performed, why it helped, and what simpler alternatives were considered.
7. **Experience and delivery**: user flow, requirements, launch plan, and cross-functional work.
8. **Quality and risk**: evaluation method, representative failures, safeguards, human escalation, privacy, and monitoring where applicable.
9. **Outcome**: verified measures with baseline, period, scope, and attribution caveats.
10. **Reflection**: what was learned, what changed, and what would happen next.
11. **Artifacts**: approved and appropriately redacted evidence that supports the story.

## Recommended Setup Sequence

1. **Set positioning**: provide the target roles, audience, preferred headline, and professional facts you want public.
2. **Inventory projects**: list potential case studies, your role, collaborators, dates, constraints, and available evidence.
3. **Select the strongest stories**: choose for relevance, depth of decision-making, and evidence, not just the use of AI.
4. **Check disclosure permissions**: remove confidential, customer-identifying, or proprietary information before drafting.
5. **Draft and verify**: write the case studies, validate claims and metrics, and distinguish measured results from estimates.
6. **Choose implementation**: decide on a simple static site or a framework after confirming page count, update workflow, maintenance, and hosting.
7. **Build and review**: make the content responsive, accessible, easy to scan, and clear about the owner's contribution.
8. **Publish deliberately**: confirm domain, hosting, public links, metadata, and permissions before deployment.

## Content and Trust Checklist

- No invented biography, job history, skills, project ownership, metrics, or testimonials.
- Every case study states the owner's actual role and credits collaborators.
- Results include context and measurement limits; estimates are labeled as estimates.
- AI claims explain the user task, the model's role, important limitations, and relevant evaluation or oversight.
- Screenshots and artifacts are approved for public sharing and have been redacted as needed.
- Contact details, resume, employer names, and project names are included only with the owner's approval.

## Technical Setup

No technology or hosting choice has been made. The current games use dependency-free HTML, CSS, and JavaScript, which are useful examples but should not dictate the portfolio architecture.

For a small portfolio, a static site can be easy to maintain and publish. Consider a framework or content system only if the number of pages, editing workflow, or desired interactions justify it. Keep the portfolio in its own repository rather than merging it into the game project without a deliberate reason.

When a site is created, a possible structure is:

```text
ai-pm-portfolio/
  README.md
  context.md
  index.html
  case-studies/
  assets/
```

This is a starting point, not a prescribed stack. Add only what the chosen implementation needs.

## Running Locally

There is no portfolio site to run yet. Once a static `index.html` exists, it can usually be opened directly in a browser. To test it through a local server from the portfolio directory:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>. A framework-based implementation should document its actual install and development commands here instead.

## Inputs Needed Before Building

Provide the items that apply; unknown details should remain placeholders:

- Public name, short bio, target AI PM roles, and preferred industries.
- Two or three projects and the owner's specific contributions.
- Verified outcomes, metric definitions, baselines, and sources.
- AI workflow details, evaluation approach, limitations, and safeguards.
- Public artifacts, resume, LinkedIn/GitHub/contact links, and sharing permissions.
- Preferred visual style, domain, hosting, and technology constraints.

Do not publish this planning document as a finished portfolio. First add verified personal content, build the site, review all claims and permissions, and then choose a deployment target.