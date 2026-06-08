# Reading Technical Proposals

`[Entry]`

## What a Proposal Should Contain

A technical proposal is a decision document. It should answer: "What are we doing, why, what are the alternatives, what does it cost, and what are the risks?"

When you receive a proposal, look for these sections:

| Section | What to Look For |
|---|---|
| **Problem statement** | Is the problem clearly defined? Can you explain it to a colleague in one sentence? |
| **Proposed solution** | What is being built or changed? Is it clear what "done" looks like? |
| **Alternatives considered** | What other options were evaluated? Why were they rejected? |
| **Trade-offs** | What do we gain? What do we give up? |
| **Timeline and milestones** | When will it be done? Are there checkpoints? |
| **Dependencies** | What must happen first? What could block progress? |
| **Cost** | People, infrastructure, licenses, ongoing maintenance. |
| **Risks** | What could go wrong? How likely is it? What is the mitigation? |

If any of these sections are missing, ask for them before approving.

## Questions to Ask

Beyond what is written, probe for what is not:

**"What alternatives did you consider?"** If the answer is "none," the team has not done due diligence. There are always alternatives.

**"What if this fails?"** Understanding the failure mode tells you the real risk. If failure means "we try a different approach," the risk is low. If failure means "customer data is corrupted," the risk is existential.

**"What is the rollback plan?"** Can we undo this change if something goes wrong? If the answer is "no," the proposal needs more thought.

**"What are we NOT building?"** Every choice to build something is a choice to not build something else. Understanding the opportunity cost is essential.

**"How will we know if it worked?"** Success metrics should be defined before the project starts, not after. "We will measure X, and the target is Y."

## Red Flags

Watch for these warning signs in proposals:

- **No alternatives.** There is always more than one way to solve a problem. A proposal that presents only one option is selling, not analyzing.
- **Vague timelines.** "Q3" is vague. "July 15 for feature-complete, August 1 for production launch" is specific. Vague timelines usually mean unclear scope.
- **No mention of maintenance.** Software is not "build once, done forever." Who maintains it? What does ongoing support cost?
- **"Industry best practice" without specifics.** Best practice according to whom? In what context? For what scale? This phrase often masks a lack of analysis.
- **All upside, no downside.** Every decision has trade-offs. A proposal that lists none is either incomplete or dishonest.

## Green Flags

Signs of a well-thought-out proposal:

- Clear articulation of what "done" means
- Honest assessment of risks with mitigation strategies
- Specific timeline with checkpoints
- Total cost of ownership (not just build cost)
- Explicit statement of what is out of scope

## Why This Matters for You

You do not need to be technical to evaluate a technical proposal. You need to think like an executive: define the problem, understand the trade-offs, verify the alternatives, and ensure the risks are acceptable.

Approve proposals that demonstrate clear thinking. Send back proposals that rely on authority ("trust us") rather than analysis.
