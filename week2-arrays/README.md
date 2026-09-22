# Week 2 – Arrays

Week 2 builds on C fundamentals through arrays, strings, character processing, and command-line arguments. These four programs apply those concepts to word scoring, readability estimation, and text encryption, with helper functions for focused calculations and validation.

---

Assessment source and submission artifacts are kept private; see [Source Code & Academic Honesty](../README.md#source-code--academic-honesty).

## Projects

| Project | Description | Status |
|---------|-------------|:------:|
| [Scrabble](./scrabble/) | Compare two player inputs using an array of letter scores. | ✅ |
| [Readability](./readability/) | Estimate reading grade level using text counts and the Coleman–Liau index. | ✅ |
| [Caesar](./caesar/) | Rotate letters with a numeric key while preserving case and non-letter characters. | ✅ |
| [Substitution](./substitution/) | Validate a substitution key and map letters while preserving case and non-letter characters. | ✅ |

> I intentionally completed both Caesar and Substitution for additional practice, although CS50 requires only one of the two.

---

## Programming Concepts Explored

- Arrays and indexed lookups
- Strings, character classification, and case conversion
- Command-line arguments and key validation
- Helper functions, parameters, and return values
- Boolean arrays for duplicate detection
- Integer and floating-point arithmetic
- Modulo arithmetic and alphabetic wraparound
- Compilation, program execution, and output verification

## Learning Objectives

The implementations demonstrate how to:

- Use arrays to associate letters with values and track previously seen characters
- Split text processing and validation into focused helper functions
- Convert character counts into a numerical readability estimate
- Validate command-line input before processing plaintext
- Transform text while preserving selected properties of the input

---

## Featured Project

⭐ **Substitution** was the most complex of the four projects in my implementation work. It combines key validation, case-insensitive duplicate detection with a Boolean array, indexed letter mapping, and preservation of plaintext case and non-letter characters.

---

## Course Information

- **Course:** Harvard CS50x – Introduction to Computer Science
- **Week:** 2 – Arrays

## Repository Structure

```text
week2-arrays/
├── README.md
├── scrabble/
│   ├── README.md
│   └── screenshots/
├── readability/
│   ├── README.md
│   └── screenshots/
├── caesar/
│   ├── README.md
│   └── screenshots/
└── substitution/
    ├── README.md
    └── screenshots/
```

Each screenshot directory contains `01-output.png`, showing a representative terminal run.

---

## Verification

**CS50 verification:** Compiled successfully, passed all applicable `check50` checks, completed `style50` and `design50` successfully, and submitted to CS50.

**Local verification:** Compiled and ran successfully in the private coursework repository; representative outputs appear in the project pages.

Each project page includes a terminal screenshot and a text example.

---

## Author

**Faizan Siddique**

[Back to repository](../README.md)
