# AI PM Portfolio: Working Context

This file is the source of truth for future planning and implementation of an AI Product Manager portfolio. It is written for the portfolio owner, collaborators, and AI coding assistants. Update it as decisions and verified facts become available.

## Project Status

The request is to set up an AI PM portfolio. The current workspace does not yet contain a portfolio website or portfolio case studies. It currently contains two independent browser games and documentation for them:

- `memory-game.html`: a responsive memory-matching game with 4 x 4 and 6 x 6 boards, a timer, move count, star rating, local best scores, keyboard support, and a persistent light/dark theme.
- `sliding-puzzle.html`: a responsive sliding-tile puzzle with 3 x 3, 4 x 4, and 5 x 5 boards, legal-move shuffling, click/tap and arrow-key controls, undo/restart, a timer, locally saved best scores, and a persistent theme.
- `PRD_dark_theme.md`, `README.md`, and `README_SLIDING_PUZZLE.md`: documentation for the existing games.

Both games use plain HTML, CSS, and JavaScript, have no external dependencies, and can be opened directly in a browser. They are examples of small interactive prototypes, not evidence of professional AI product-management work unless the owner explicitly chooses to present them that way.

`README_AI_PM_PORTFOLIO.md` describes the proposed portfolio setup. It is planning documentation only; it does not mean the portfolio site has been built or deployed. Keep the portfolio separate from the game project unless the owner decides to combine them.

## Portfolio Goal

Create a credible, easy-to-scan portfolio that helps hiring teams understand the owner's product judgment and ability to deliver AI-enabled products. The portfolio should show how the owner frames user and business problems, makes decisions under constraints, works with design and engineering, evaluates outcomes, and learns from results.

The portfolio should prioritize a small number of complete, evidence-backed stories over a large gallery of shallow project summaries. It should make the owner's contribution clear without implying sole ownership of team outcomes.

## Intended Audience

Primary readers are product, AI product, and hiring leaders evaluating the owner's fit for AI PM roles. They may scan quickly, so each project should make its problem, the owner's role, the decision, and the outcome easy to find.

Specific job titles, seniority, industries, geography, and target employers have not been provided. Do not assume or invent them.

## Recommended Portfolio Sections

1. **Home / positioning**: a concise, factual statement of product focus, relevant strengths, and the kinds of problems the owner wants to work on.
2. **Case studies**: two or three detailed examples, selected for relevance and evidence rather than novelty alone.
3. **AI product work**: experiments, evaluations, prototypes, or product analyses that demonstrate applied AI PM judgment. Label personal work, coursework, and professional work accurately.
4. **About**: a short professional narrative based on facts the owner supplies.
5. **Resume and contact**: links supplied and approved by the owner.

This is a starting information architecture, not a fixed design or a claim that these sections already exist.

## Case Study Standard

Use a consistent narrative for each case study:

1. **Summary**: product, user, problem, and outcome in a few lines.
2. **Context**: business situation, users, constraints, timeline, and team.
3. **Role and ownership**: the owner's specific responsibilities and collaborators.
4. **Problem discovery**: research, usage evidence, customer feedback, and assumptions.
5. **Opportunity and strategy**: why this problem mattered, options considered, and prioritization rationale.
6. **AI suitability**: why AI was appropriate (or not), the intended workflow, and what non-AI alternatives were considered.
7. **Solution and delivery**: user experience, product scope, launch approach, and cross-functional execution.
8. **AI system decisions, when relevant**: model or approach selection, data needs, retrieval or tools, cost and latency constraints, and known limitations. Include only details that are true and appropriate to disclose.
9. **Evaluation and safety**: quality measures, test cases, failure modes, human review or override, privacy, security, and monitoring that actually applied.
10. **Results**: verified outcomes with baselines, time period, sample size, and attribution caveats where available.
11. **Learning**: what changed, what did not work, and what the owner would do next.
12. **Evidence**: approved screenshots, artifacts, research summaries, prototypes, or links, with confidential material removed.

Not every project needs every technical detail. Explain the decisions that mattered for that project and name unknowns honestly.

## AI PM Signals to Demonstrate

Choose evidence that fits the owner's real work. Useful signals may include:

- Selecting problems where AI creates user value beyond a conventional workflow or rules-based solution.
- Translating user needs into product requirements and measurable success criteria.
- Designing for uncertainty, latency, quality variation, fallback, and human control.
- Defining evaluation that reflects real user tasks, not only model benchmarks.
- Balancing quality, cost, speed, privacy, safety, and usability.
- Planning data feedback, monitoring, incident handling, and iterative improvement.
- Coordinating product, design, engineering, data, research, legal, and operations partners.
- Communicating trade-offs and setting expectations about model limitations.

These are prompts for evidence gathering, not claims about the owner's existing skills.

## Content Integrity and Confidentiality

- Never fabricate employers, titles, responsibilities, product launches, users, metrics, testimonials, or business results.
- Distinguish the owner's individual contribution from team work.
- Label estimates, simulations, public-data analyses, coursework, and personal prototypes explicitly.
- For every metric, record its source, baseline, time window, population, and limitations when known. Do not claim causality without evidence.
- Remove customer data, internal screenshots, unreleased plans, credentials, and proprietary details unless the owner has explicit permission to share them.
- When confidentiality prevents specifics, describe the decision and method at an appropriate level and state the limitation.
- Use placeholders for missing facts; ask the owner to confirm them before publishing.

## Experience and Design Principles

- Make the work and the owner's judgment the focus, not decorative AI imagery or unsupported claims.
- Keep navigation clear and pages readable on mobile and desktop.
- Use accessible semantic structure, visible keyboard focus, strong contrast, descriptive links, and reduced-motion support where relevant.
- Make case studies easy to scan with summaries, headings, concise paragraphs, and relevant artifacts.
- Avoid generic AI language. Prefer specific users, workflows, trade-offs, evidence, and outcomes.
- Do not add fabricated endorsements, logos, metrics, or project imagery.

## Technical Direction: Not Yet Decided

The existing game examples are static single-file pages, but that does not require the portfolio to use the same architecture. Choose an implementation only after confirming desired scope, maintenance comfort, content volume, hosting, and whether the owner wants a static site or a framework.

For a low-maintenance first version, a static site is a reasonable option. A framework may be appropriate if the portfolio needs many case-study pages, a content system, or richer interactions. No framework, domain, hosting provider, analytics service, or deployment pipeline has been selected.

Keep the portfolio in a dedicated repository or clearly separate directory so that game demos and portfolio content are not confused. Do not add dependencies or publish the site without the owner's direction.

## Information Needed From the Owner

- Preferred name, professional headline, short biography, and location or time zone if they want it public.
- Target roles, seniority, industries, and audience.
- Two or three projects they are allowed to discuss, with dates, goals, constraints, team, and their role.
- Evidence and approved outcome metrics for each project.
- Which projects involved AI, and what the AI did in the user workflow.
- Public artifacts, screenshots, demos, writing, or prototypes they have permission to share.
- Resume, LinkedIn, GitHub, email, and other public links to include.
- Preferred visual direction, accessibility requirements, domain, hosting, and technology constraints.

## Instructions for Future AI Work

- Treat this document as a brief, not as a source of personal career facts.
- Read the existing project files before making changes; do not mistake the game repository for the portfolio implementation.
- Ask focused questions when a missing fact would change the content or architecture. Otherwise, mark it as a placeholder.
- Preserve the existing game files and game READMEs unless the owner explicitly asks to change them.
- Keep portfolio content truthful, evidence-led, privacy-conscious, and explicit about the owner's role.
- Before publishing, verify every public claim, link, artifact, and permission with the owner.