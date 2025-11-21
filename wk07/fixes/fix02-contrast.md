# Fix 02: Add Task Button Contrast (WCAG 1.4.3)

**Backlog ID**: 2
**WCAG Criterion**: 1.4.3 Contrast (Minimum, Level AA)
**Priority**: 9 

---

## Problem Statement
Add button text color #6c757d on blue background #017fc0 = 1.07:1 contrast ratio.
**Fails**: WCAG AA requires 4.5:1 or more for normal text.

**Evidence**:
- axe DevTools: color-contrast (Serious)
- WebAIM Contrast Checker: 1.07:1 (Fail AA)
- Screenshot: `wk07/evidence/contrast-before.png`

---

## Target State
Contrast ratio ≥ 4.5:1 (AA) or ≥ 7:1 (AAA).

---

## Solution
Override Pico.css button color with darker gray or custom color.

**Option A**: White (#FFFFFF = 4.68:1 contrast, passes AA)

**Chosen**: Option A (white) matches white text.

---

## Implementation

### Before (Current CSS)
Pico.css default:
```css
button {
  color: #6c757d; /* 4.2:1 contrast */
}
