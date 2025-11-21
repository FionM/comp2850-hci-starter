# WCAG 2.2 AA Checklist - Week 7

**Date**: [2025-11-21]
**Scope**: Task manager (add, edit, delete flows)
**Tester**: [Fion McReynolds]

---

## Perceivable (Principle 1)

### 1.1 Text Alternatives
| Criterion | Level | Status | Evidence | Notes |
|-----------|-------|--------|----------|-------|
| 1.1.1 Non-text Content | A | n/a | Path to image doesn't exist | Will ensure alt text is included |


### 1.3 Adaptable
| Criterion | Level | Status | Evidence | Notes |
|-----------|-------|--------|----------|-------|
| 1.3.2 Meaningful Sequence| A | Pass| Skip to main content, Add task, Delete task | A logical order |

### 1.4 Distinguishable
| Criterion | Level | Status | Evidence | Notes |
|-----------|-------|--------|----------|-------|
| 1.4.3 Contrast | AA | Fail | Add task text colour #6c757d = 1.11:1| Minimum of 4.5:1 to pass | Change text colour
---

## Operable (Principle 2)

### 2.1 Keyboard Accessible
| Criterion | Level | Status | Evidence | Notes |
|-----------|-------|--------|----------|-------|
| 2.1.1 Keyboard | A | Pass | Can access all features via keyboard | Tested: add, delete |
| 2.1.2 No Keyboard Trap | A | Pass | No traps detected | Can Tab out of anything / use keyboard shortcuts to close open tabs |

### 2.4 Navigable
| Criterion | Level | Status | Evidence | Notes |
|-----------|-------|--------|----------|-------|
| 2.4.1 Bypass Blocks | A | Pass | When using tab option to skip to main content | Tested with keyboard |
| 2.4.2 Page Titled | A |  Pass | HTMX Docs and WCAG 2.2 describe the webpages clearly | Tested with keyboard and with mouse |
| 2.4.6 Headings and Labels | AA | Partial | Title shows an example of what to enter and second input has a label to show what it is | Contrast fail 1.11. This needs to be changed|

---

## Understandable (Principle 3)

### 3.2 Predictable
| Criterion | Level | Status | Evidence | Notes |
|-----------|-------|--------|----------|-------|
| 3.2.1 On Focus | A | Pass | Doesn't change context unless button is clicked | Only changes conext when the user clicks the button |
| 3.2.2 On Input | A | Pass | No input change unless button is clicked | Task only added if the button is clicked |

---


---
