#3) Portfolio Case Study (/docs/case-study.md)
# AI Code Trust Auditor — Case Study

## Problem
AI-generated code increases speed but introduces:
- security risks
- poor structure
- lack of validation

Developers often trust output without verification.

## Solution
A browser-based tool that:
- analyzes code using deterministic rules
- assigns a Trust Score
- explains risks and how to fix them

## Key Features
- Rule-based risk detection
- Insight summary (plain language)
- Fix guidance (actionable)
- Execution plan (step-by-step)

## Architecture
Single pipeline:
Input → Analyze → Score → Insights → Render

No backend. No APIs. Fully client-side.

## Design Decisions
- Minimal rules (avoid noise)
- Deterministic logic (no randomness)
- Enterprise UI (sidebar + tabs)

## Impact
- Improves code safety awareness
- Encourages structured thinking
- Demonstrates system design skills

## What I Learned
- Simplicity > complexity
- UX clarity improves adoption
- Evaluation tools are high-value

## Future Improvements
- Multi-language support
- Export reports (PDF)
- Session tracking