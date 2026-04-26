# Sweet Shop — QA Audit Report

**Type:** UI / Accessibility / Performance
**Site:** sweetshop.netlify.app
**Auditor:** Ramone Scott — QA Engineer

## Summary
Full QA audit of a retail e-commerce web application. Covers bug documentation, WCAG 2.1 AA accessibility compliance, performance analysis, and production readiness verdict.

## Findings
- 9 bugs documented with severity ratings
- WCAG 2.1 AA accessibility score: 4/10
- Production readiness score: 4/10
- 5 quick wins identified (each under 30 minutes to fix)

## Key Bugs Found
- Broken product image firing 404 on every page load (whan.jpg typo)
- Legacy Google Analytics UA tag collecting zero data since 2023 (sunset)
- 16 product images missing alt text — WCAG 1.1.1 failure
- City dropdown typo in billing form ('Swansow' instead of 'Swansea')
- No basket confirmation feedback after adding items

## Tools Used
Browser-based analysis, HTTP request inspection, WCAG 2.1 AA framework

---
*Ramone Scott · QA Engineer · Jamaica · Available for freelance audits*
