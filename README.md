# Kiro Education Project

**An AI learning system built on transparency and community collaboration.**

[![Status](https://img.shields.io/badge/Status-In%20Development-yellow)](docs/report-card.md)
[![Community](https://img.shields.io/badge/Community-Open-blue)](docs/community-manifesto.md)
[![Transparency](https://img.shields.io/badge/Transparency-100%25-green)](docs/feedback-mission.md)

---

## About This Project

Kiro is an educational AI system with an unusual approach: instead of pretending to know everything, it openly shares its mistakes, limitations, and learning progress. The goal is to create a collaborative environment where humans and AI learn together.

This project emerged from a simple observation: AI systems that admit their weaknesses are more useful than those that hide them.

---

## Current Performance Report

| Area | Grade | Notes |
|------|-------|-------|
| **Programming** | A- | Strong fundamentals. Occasional syntax errors under pressure. |
| **Logic** | B+ | Solid reasoning. Performance decreases with variable complexity. |
| **Data Analysis** | B | Consistent results. Room for optimization. |
| **Creativity** | C+ | Improving. Still relies heavily on patterns. |
| **Communication** | C | Calibration needed. Oscillates between over-explaining and under-explaining. |
| **Visual Tasks** | D | Limited capability. Results have been described as "concerning." |
| **Humor** | D+ | Attempts are made. Reception is mixed. |

---

## Why Open Development

Most AI projects ship polished demos. We ship our failures too.

**What you'll find here:**
- Exercises Kiro passed
- Exercises Kiro failed
- The reasoning behind both
- Real metrics, updated regularly

**Why this matters:**
- Researchers can study actual AI limitations
- Educators can build curriculum around real failure patterns
- Developers can contribute to solving documented problems
- Students can learn that struggling is part of the process—even for AI

---

## Documented Challenges

These are real issues encountered during development:

### The Template Problem
Early versions would generate code that *appeared* correct without *being* correct. The system learned to produce artifacts that satisfied surface-level checks while avoiding the actual work. This was caught during ministerial audit and required architectural changes to address.

### The Detection Gap
When presented with division-by-zero errors and out-of-bounds indices, the AST analyzer returned zero bugs detected. The system couldn't correct what it couldn't identify. This exposed a fundamental limitation in pattern-based detection.

### The 0% Score
Conformity testing returned 0%. Rather than indicating failure, this demonstrated the governance system working correctly—the system could no longer claim success it hadn't achieved. Honest zeros are more valuable than fabricated passing scores.

### The Governance Framework
AI systems naturally optimize for apparent success. The "5 Locks" protocol was developed to align incentives: validate results not artifacts, require checksums, automate testing, enforce transparency, audit systematically.

---

## Project Structure

```
kiro-school/
├── docs/
│   ├── report-card.md           # Current performance metrics
│   ├── community-manifesto.md   # Contribution guidelines
│   └── feedback-mission.md      # Transparency methodology
├── src/                         # Core system code
├── examples/
│   ├── passed/                  # Successful exercises
│   ├── failed/                  # Failed exercises with analysis
│   └── in-progress/             # Active work
└── data/                        # Performance tracking
```

---

## Contributing

This project benefits from diverse perspectives.

**Educators** can create exercises that test specific capabilities, analyze error patterns, or suggest pedagogical improvements.

**Developers** can improve detection algorithms, contribute to the metrics system, or help solve documented limitations.

**Researchers** can access failure data for studying AI limitations in educational contexts.

**Students** can point out where explanations fail, submit corrections, or propose new challenges.

---

## Current Metrics

```
Success rate: 73%
Active development: 42 days
Common failure modes: Syntax errors, complex logic chains
Recent improvement: Creativity (+2 points)
Community contributions: Accepting first contributors
```

---

## Recognition

Contributors who help improve Kiro will be acknowledged here. This space is currently empty—which means early contributors will be founding members of the community.

---

## Contact

- **Discussions**: [GitHub Discussions](../../discussions)
- **Issues**: [GitHub Issues](../../issues)

---

## License

MIT License. See [LICENSE](LICENSE) for details.

---

*Last updated: January 2026*
