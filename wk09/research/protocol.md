# Evaluation Protocol — Week 9 Pilots

**Module**: COMP2850 HCI
**Activity**: Task-based usability pilots
**Date**: [YYYY-MM-DD]
**Researcher**: [Fion McReynolds]

---

## Purpose

Evaluate task manager usability and accessibility through structured pilots. Data will inform Week 10 redesign and assessment submission.

## Consent Script 

**Lawful basis**: Legitimate interest (educational research) + informed consent

**Please read below to the tester**

Hello I am Fion McReynolds a student at the University of Leeds undergoing an acccessibility report on the Task Manager Website.

I wish to investiage whether the website is accessible for all.
If you agree to test the website the following will happen:

- I will describe the tasks you are going to complete. 
- There will be 4 in total and it will take you approximately 5 minutes per task. 
- A reminder that I am testing the accessibility of the website not you.

- In regards to your data, I am collecing the following:
   - How long it takes you to complete the task
   - If you complete each task successfully 
   - Any issues you may come across
   - Your confidence rating after each task
   - My own notes on things I saw you struggle with or accessibility issues

- I would like to make it clear I will not be collecting any personal information such as 
   - Name, email or student ID
   - Audio or screen recordings
   - Any device details other than 'scrren reader' or 'keyboard only'

- You can stop at any time with no questions asked and any data realting to you will be deleted 
- Is there any questions?
- Finally, are you happy to proceed?

Add consent to consent.md
 

**Before starting**, confirm:
- [ ] It has been explained that you are testing the to-do list and not the developer (myself) 
- [ ] The tasks you will complete have been described to you: Add, Edit, Find, Delete
- [ ] You are aware of all the data I will be collecting (times, clicks, observations - no PII)
- [ ] You are aware of your right to withdraw  (stop anytime, data deleted)
- [ ] Participant verbally consents

**Record**: Participant pseudonym (P1, P2...), date, consent confirmed (initials)

---

## Procedure

### Setup (5 minutes)
1. **Assign mode**: Participant 1 → HTMX, Participant 2 → No-JS (alternate)
2. **Disable JS if needed**: Chrome DevTools → Settings → Disable JavaScript
3. **Set session ID**: Open browser DevTools Console, paste:
   ```javascript
   document.cookie = "sid=P1_7a9f; path=/";  // P1 = Participant 1, random suffix

