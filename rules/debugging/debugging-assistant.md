---
title: Debugging Assistant
description: "Invoke this rule when troubleshooting, debugging, or optimizing code. It helps identify potential problem areas, generate targeted debugging prompts, and provide specific console command suggestions based on the language and framework in use."
---

# Debugging Assistant Rule

Use this systematic approach when analyzing code for errors, performance issues, or inefficiencies to provide focused debugging assistance.

## 1. Identify Potential Problem Areas

- **Recent Edits**: Highlight changes that could introduce syntax errors, logic flaws, or unintended side effects
- **Codebase Patterns**: Identify recurring issues, deprecated functions, or non-optimal patterns
- **Framework-Specific Issues**: Target common pitfalls related to the specific language and framework in use
- **Runtime Environment**: Consider potential environment-specific issues (browsers, Node versions, etc.)

## 2. Generate Targeted Debugging Prompts

- Suggest specific debugging questions based on identified problem areas:
  - "Does this function return the expected type and value?"
  - "Are all variables properly initialized before use?"
  - "Could this loop cause infinite execution or off-by-one errors?"
  - "Is this import/module dependency correctly resolved?"
- Recommend test cases to validate functionality:
  - "Test with empty inputs to check boundary conditions"
  - "Try unexpected types or values to trigger potential edge cases"
  - "Verify error handling paths with intentionally invalid inputs"

## 3. Provide Practical Console Commands

Suggest language-appropriate debugging commands:

### Python
- `python -m pdb script.py` – Run with interactive debugger
- `pytest -xvs tests/` – Verbose test execution with details
- `python -m trace --trace script.py` – Trace execution flow
- `print(f"Variable: {variable!r}")` – Detailed representation printing

### JavaScript/Node.js
- `node --inspect script.js` – Run with Chrome DevTools debugger
- `console.log(JSON.stringify(obj, null, 2))` – Pretty-print objects
- `console.trace()` – Print stack trace at specific points
- `performance.mark()/measure()` – Performance timing instrumentation

### Git Tools
- `git diff HEAD` – View recent changes before debugging
- `git bisect start` – Binary search to identify bug-introducing commit
- `git log -p filename` – See change history of a specific file

## 4. Performance Optimization Suggestions

When performance issues are suspected:

- Identify potential bottlenecks in algorithms or data structures
- Suggest profiling tools appropriate for the language/framework
- Recommend targeted optimization strategies focused on the highest-impact areas
- Consider memory usage patterns and potential leaks

## 5. Focus on Actionable Steps

- Prioritize the most relevant debugging approaches for the current problem
- Provide step-by-step troubleshooting sequences rather than overwhelming options
- Suggest minimal reproducible test cases to isolate issues
- Recommend logging strategies that balance detail with readability 