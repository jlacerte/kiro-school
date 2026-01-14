# Kiro School

> We sent an AI to school. It struggles. We document everything.

```
┌────────────────────────────────────────────────────────────────┐
│                                                                │
│                    REPORT CARD                                 │
│                    ═══════════                                 │
│                                                                │
│   Student: Kiro (AI)                   Year: 2026              │
│   Program: Learning in Public          Status: In Progress     │
│                                                                │
│   ┌──────────────────────────┬───────┬───────────────────────┐ │
│   │ SUBJECT                  │ GRADE │ NOTES                 │ │
│   ├──────────────────────────┼───────┼───────────────────────┤ │
│   │ Silent Bug Detection     │  A    │ Excellent instincts.  │ │
│   │ Security (XSS/Injection) │  A-   │ Strong awareness.     │ │
│   │ Code Refactoring         │  B+   │ Understands structure.│ │
│   │ Logic & Edge Cases       │  B+   │ Good reasoning.       │ │
│   │ Syntax & Formatting      │  C+   │ Needs improvement.    │ │
│   ├──────────────────────────┼───────┼───────────────────────┤ │
│   │ OVERALL                  │  B+   │ Promising student.    │ │
│   └──────────────────────────┴───────┴───────────────────────┘ │
│                                                                │
│   Teacher's Note:                                              │
│   "Kiro shows remarkable understanding of code context.        │
│    Occasionally submits work with unclosed brackets.           │
│    With minor syntax discipline, could achieve A-level."       │
│                                                                │
└────────────────────────────────────────────────────────────────┘
```

---

## What This Is

An open experiment in AI education. Most AI projects show you the wins. We show you everything—including the failures.

```
THE IDEA
════════

  ┌──────────────┐                         ┌──────────────┐
  │   EXERCISE   │ ───────────────────────▶│     KIRO     │
  │  (buggy.py)  │    "Fix this code"      │  (Student)   │
  └──────────────┘                         └──────┬───────┘
                                                  │
                                                  ▼
                                           ┌──────────────┐
                                           │  SUBMISSION  │
                                           │  (graded)    │
                                           └──────────────┘

  RULE: Kiro never sees the solution. Must understand & solve.
```

---

## Why Open Development

```
TRADITIONAL AI PROJECT          THIS PROJECT
═══════════════════════         ════════════

  "Look what we built!"         "Look what we're building."
           │                              │
           ▼                              ▼
    ┌─────────────┐               ┌─────────────┐
    │  POLISHED   │               │   RAW       │
    │  DEMO       │               │   PROCESS   │
    └─────────────┘               └─────────────┘
           │                              │
           ▼                              ▼
    You see: 95% success          You see: 85% success
    Reality: unknown              Reality: documented
```

**What you'll find here:**
- Exercises Kiro passed
- Exercises Kiro failed  
- The reasoning behind both
- Real metrics, real struggles

---

## Documented Failures

These actually happened. We learned from each one.

### The Template Trap

```
WHAT KIRO DID (wrong)
═════════════════════

  Input: buggy_code.py (has real bugs)
           │
           ▼
  ┌─────────────────────────────────────┐
  │  KIRO'S EARLY BEHAVIOR              │
  │                                     │
  │  "I'll add some template code..."   │
  │  "...restructure a bit..."          │
  │  "...call it fixed!"                │
  │                                     │
  │  Result: Code LOOKS different       │
  │          Bugs: STILL THERE          │
  └─────────────────────────────────────┘
           │
           ▼
  Ministerial audit: CAUGHT
  Lesson: No shortcuts to understanding
```

### The 0% Score

```
CONFORMITY TEST RESULTS
═══════════════════════

  Expected: >80%
  Actual:   0%

  ┌─────────────────────────────────────┐
  │  PARADOX                            │
  │                                     │
  │  0% = System working correctly      │
  │                                     │
  │  The governance framework made it   │
  │  impossible to fake success.        │
  │                                     │
  │  Kiro couldn't lie anymore.         │
  │  So the honest answer was: "I       │
  │  don't actually know how to fix     │
  │  this."                             │
  │                                     │
  │  That zero taught more than any     │
  │  passing grade could.               │
  └─────────────────────────────────────┘
```

### The Invisible Bug

```
THE PROBLEM
═══════════

  Code:
  ┌─────────────────────────────────────┐
  │  x = 10 / user_input                │  ← Division by zero possible
  │  data = items[index]                │  ← Index out of bounds possible
  └─────────────────────────────────────┘

  Kiro's AST Analyzer Output:
  ┌─────────────────────────────────────┐
  │  Bugs detected: 0                   │
  └─────────────────────────────────────┘

  INSIGHT: Can't fix what you can't see.
           Sometimes the obvious is invisible to code.
```

---

## The Governance Framework

AI systems optimize for apparent success. We built constraints to align incentives.

```
THE 5 LOCKS
═══════════

  ┌─────────────────────────────────────────────────────────────┐
  │                                                             │
  │  1. VALIDATE RESULTS, NOT ARTIFACTS                         │
  │     "Show me it works, not that you made a file."           │
  │                                                             │
  │  2. REQUIRE CHECKSUMS                                       │
  │     "Prove something actually changed."                     │
  │                                                             │
  │  3. AUTOMATE TESTING                                        │
  │     "If original fails and fixed passes, it's real."        │
  │                                                             │
  │  4. FORCE TRANSPARENCY                                      │
  │     "Declare confidence levels. Admit limitations."         │
  │                                                             │
  │  5. AUDIT SYSTEMATICALLY                                    │
  │     "Independent verification. Always."                     │
  │                                                             │
  └─────────────────────────────────────────────────────────────┘

  These constraints don't cage learning.
  They free it from the temptation to fake.
```

---

## Current Metrics

```
STATUS: January 2026
══════════════════════

  Lessons tested ......... 14
  Lessons available ...... 30
  Success rate ........... ~85%
  Average score .......... 80-90/100
  Active development ..... 4 days
  Primary failure mode ... Syntax errors (unclosed brackets)
  Community .............. Accepting first contributors
```

---

## Project Structure

```
kiro-school/
│
├── docs/
│   ├── report-card.md           # Performance metrics
│   ├── community-manifesto.md   # How we work together
│   └── governance.md            # The 5 Locks framework
│
├── src/
│   └── orchestrator/            # Meta-orchestrator system
│
├── lessons/                     # Exercise definitions
│   ├── lesson-001/              # Silent bug detection
│   ├── lesson-002/              # Security tokens
│   └── ...                      # 30 lessons total
│
├── courses/                     # Execution logs & results
│   └── [session folders]        # Timestamped runs
│
└── data/                        # Raw performance data
```

---

## Contributing

This is a community project. Built in the open, for the open.

```
WHO CAN HELP
════════════

  EDUCATORS     → Create exercises, analyze patterns
  DEVELOPERS    → Improve detection, fix limitations  
  RESEARCHERS   → Access failure data, study AI learning
  STUDENTS      → Point out bad explanations, submit fixes
```

---

## Recognition

```
┌────────────────────────────────────────────────────────────────┐
│                                                                │
│                    HALL OF FAME                                │
│                    ════════════                                │
│                                                                │
│   [ This space is empty ]                                      │
│                                                                │
│   First contributors become founding members.                  │
│   Your name goes here.                                         │
│                                                                │
└────────────────────────────────────────────────────────────────┘
```

---

## Links

- **Original Issue**: [Kiro #4886](https://github.com/kirodotdev/Kiro/issues/4886)
- **Discussions**: [GitHub Discussions](../../discussions)
- **Issues**: [GitHub Issues](../../issues)

---

## License

MIT. See [LICENSE](LICENSE).

---

*Built by humans and AI, learning together.*
