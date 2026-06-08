# How to Talk to Engineers

`[Entry]`

## Describe Outcomes, Not Solutions

The most common communication mistake: telling engineers *how* to solve a problem instead of describing *what* the problem is.

| Less Effective | More Effective |
|---|---|
| "Make the button bigger" | "Users are missing the checkout button. Our cart abandonment rate is 40% at that step." |
| "Add a search bar here" | "Users cannot find what they need. They spend 90 seconds navigating menus that should take 10 seconds." |
| "Use React" | "We need the interface to respond instantly. Current page load is 8 seconds." |
| "Copy what Competitor X does" | "Competitor X converts at 3x our rate. Their checkout has 2 steps; ours has 6." |

When you describe a solution, you constrain the engineer to one approach. They might know a better one. When you describe the outcome, you give them the problem and let them find the best solution.

## Share Context

Engineers make better decisions when they understand the "why."

**Who is this for?** "This feature is for first-time users on mobile devices, typically in areas with slow internet." This changes every design decision.

**Why now?** "Our biggest competitor launches this feature next month." A deadline focuses effort differently than "whenever you get to it."

**What happens if we get it wrong?** "If this calculation is off, we overcharge customers." The stakes determine how much testing and validation are needed.

**What does success look like?** "Success is a 20% reduction in support tickets about password resets." A measurable goal lets the team know when they are done.

## Be Specific

Vague requests produce vague results.

| Vague | Specific |
|---|---|
| "Make it faster" | "Page load should be under 3 seconds on a 4G connection" |
| "Make it user-friendly" | "A new user should complete signup in under 2 minutes with no help" |
| "It should be secure" | "User data must be encrypted and compliant with PDPA" |
| "Fix the bug" | "When a user clicks 'Save' twice quickly, the record duplicates. Here is how to reproduce it: ..." |

## Ask Questions, Make Decisions

Engineers will present you with options and trade-offs. Your job is to make decisions. You do not need to be technical to decide:

- "Option A takes 2 weeks but limits future flexibility. Option B takes 6 weeks but is more extensible." -- Which matters more right now: speed or flexibility?
- "We can fix this properly (3 weeks) or patch it temporarily (2 days, but it might break again)." -- What is the cost of it breaking again versus the cost of waiting 3 weeks?

These are business decisions, not technical ones. You are qualified to make them.

## Why This Matters for You

Clear communication between business and engineering is the single biggest lever for project success. Not budget, not technology, not team size. Communication.

The formula: describe the problem, share the context, define success, and let engineers propose solutions. Then make timely decisions on the trade-offs they present.
