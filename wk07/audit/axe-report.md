# axe DevTools Audit Report — Week 7

**Date**: [2025-11-14]
**URL**: http://localhost:8080/tasks
**Tool**: axe DevTools 4.x
**Scope**: Full page scan (add form + task list)


---

## Summary
- **Critical**: 1
- **Serious**: 2
- **Moderate**: 
- **Minor**: 0
- **Total**: 3 issues


---

## Critical Issues
### Issue 1: Images must have alternative text

**Element**: '<img src="/static/img/icon.png" width="16" height="16">'
**Rule**: 'Non text content' (WCAG 1.1.1)
**Description**: Image does not have alternative text
**Impact**: People who use a screen reader will not know the image is on the web page
**Fix**: Include alt text in the declaration of the image
**Status**: **CONFIRMED** - Path to image does not exist therefore no image is displayed - Add to backlog as high severity

---

## Serious Issues
### Issue 2: Minimum colour contrast not met

**Element**: '<button type="submit">Add Task</button>'
**Rule**: 'Colour contrast' (WCAG 1.4.3)
**Description**: Button does not meet minimum colour contrast = 1.1:1 which fails AA
**Impact**:  People who suffer with low vision will find it difficult to dinguish between the foreground and background colours
**Fix**: Change text colour to #FFFFFF (white, 23:1 contrast)
**Status**: **CONFIRMED** - Add to backlog as medium severity

### Issue 3: Links must have discernible text

**Element**: '<a href="/about"></a>'
**Rule**: 'Link purpose' (WCAG 2.4.4, 4.1.2)
**Description**: Link exists in the bottom left of the screen
**Impact**:  Text may not be picked up for screen readers
**Fix**: Ensure screen readers can see the links
**Status**: **FALSE POSITIVE** - Hovering over links reveals descriptions in white boxes at the bottom of the screen. Verify manually for screen readers

---

## Minor issues
None detected.

---

## Actions
1. **High priority (Issue 1)**: Ensure path to image exists and add alternative text if required. Add to backlog
2. **Medium priority (Issue 2)**: Fix contrast ration for button. Add to backlog
3. **False positive (Issue 3)**: Verify screen readers can access text for links

---

**Next step**: Manual testing