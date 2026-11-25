# Week 3 – Algorithms

Week 3 moved my work from arrays and strings into algorithm analysis and election simulations. I compared Bubble sort, Merge sort, and Selection sort across different input orders, then applied arrays, strings, and helper functions to plurality and ranked-choice voting.

Assessment source and submission artifacts are kept private; see [Source Code & Academic Honesty](../README.md#source-code--academic-honesty).

## Projects

| Project | Description | Status |
|---------|-------------|:------:|
| [Sort](./sort/) | Compare three sorting algorithms across sorted, reversed, and randomized inputs. | ✅ |
| [Plurality](./plurality/) | Count votes and identify the candidate or candidates with the most votes. | ✅ |
| [Runoff](./runoff/) | Tabulate ranked-choice ballots and eliminate candidates through successive rounds. | ✅ |
| [Tideman](./tideman/) | Build pairwise preferences and lock winning pairs while preventing cycles in a directed graph. | ✅ |

---

## Programming Concepts Explored

- Bubble sort, Merge sort, and Selection sort
- How input order affects observed running time
- Algorithmic complexity and experimental timing comparisons
- Arrays, strings, helper functions, and clear function responsibilities
- Plurality vote counting and ranked-choice tabulation
- Active candidates, elimination, and transferring each ballot to its next active preference
- Pairwise preferences, victory strength, directed graphs, recursion, and reachability

## Featured Project

⭐ **Tideman** was the flagship challenge of my Week 3 Problem Set. It was optional, and I chose to take it on. At first the problem seemed manageable; the real difficulty arrived at `lock_pairs()` and its recursive helper, `can_reach()`. Reasoning about paths through a directed graph, deciding whether a proposed edge would make an existing node reachable from itself, and preventing a cycle before adding that edge took me two days to understand and implement correctly.

Sort, Plurality, and Runoff felt comparatively straightforward to me. Tideman demanded a different kind of persistence: tracing recursive reachability through edges that had already been locked, then applying that reasoning consistently to each new pair. I eventually completed the challenge, passed all 17 `check50` checks, received no `style50` warnings, and submitted it.

## Learning Objectives

The projects show how I:

- Compared sorting behavior on inputs with different sizes and orderings, while treating measured timings as experiments rather than universal guarantees
- Used arrays, strings, and focused function responsibilities to represent candidates and votes
- Repeatedly counted active votes, eliminated a lowest-ranked candidate, and allowed ballots to transfer to the next active choice
- Represented pairwise victories as directed edges and reasoned about graph reachability before locking each edge

## Course Information

- **Course:** Harvard CS50x – Introduction to Computer Science
- **Week:** 3 – Algorithms

## Repository Structure

```text
week3-algorithms/
├── README.md
├── sort/
│   ├── README.md
│   └── screenshots/ (11 timing comparisons)
├── plurality/
│   ├── README.md
│   └── screenshots/
├── runoff/
│   ├── README.md
│   └── screenshots/
└── tideman/
    ├── README.md
    └── screenshots/
```

Screenshots are original terminal evidence copied from the private coursework repository. Assessed source code and complete solutions are not included.

---

## Verification

- **Sort:** All `check50` checks passed.
- **Plurality:** 13 `check50` checks passed.
- **Runoff:** 25 `check50` checks passed; `style50` reported “Looks good!”.
- **Tideman:** 17 `check50` checks passed; `style50` produced no warnings; submission confirmed.

---

## Author

**Faizan Siddique**

[Back to repository](../README.md)
