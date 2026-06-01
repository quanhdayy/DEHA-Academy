# Agent AI Marketing Onboarding/Training Flow

## Scope
This document is the source-of-truth onboarding/training flow for new marketing staff, coordinated by:
- Marketing Leader
- New staff (candidate)
- Agent AI Marketing

Main channels:
- **Google Sheet**: onboarding plan, submission links, review, result, status
- **Message Base**: automatic notifications/reminders/feedback

## Updated onboarding flow (TO-BE)
1. Marketing Leader or system initializes onboarding path for new staff.
2. Agent AI receives new staff info and corresponding onboarding plan.
3. Agent AI automatically sends materials, lessons, assignments, and daily instructions.
4. Candidate completes assigned exercises.
5. Agent AI tracks progress.
6. If candidate is delayed or misses deadline, Agent AI automatically reminds them.
7. Agent AI receives the submission.
8. Agent AI compares the submission against configured evaluation criteria for the day.
9. Agent AI produces an initial review and classifies the result as:
   - Passes criteria
   - Not passed, needs revision (with revision suggestions)
10. **Marketing Leader reviews Agent AI’s generated review** and can:
   - Approve the review
   - Reject/edit the review before release
11. After the overall review is finalized, Agent AI must provide:
   - Detailed review comments
   - Concrete content-editing guidance
   - Related learning materials for weak knowledge areas
   - Knowledge-check questions for those weak areas
12. Candidate answers the knowledge-check:
   - If answers are sufficient for all identified weak areas, candidate **passes the knowledge portion** and must revise and resubmit the content assignment.
   - If answers are insufficient, Agent AI continues assigning targeted learning materials and knowledge-check questions.
   - Each weak area keeps an independent counter. After **3 consecutive insufficient knowledge-check submissions** for the same weak area, Agent AI escalates to Marketing Leader for manual coaching direction.
13. Candidate revises and resubmits the content assignment.
14. Agent AI receives revised submission and re-evaluates.
15. Loop continues until assignment passes.
16. If passed, Agent AI confirms completion of the lesson/day and automatically moves to the next lesson/assignment.
17. If day 7 ends and all completion conditions are satisfied, Agent AI confirms completion of onboarding and transitions staff to the marketing operations phase.

## Decision logic summary
- **Content quality gate**: submission must pass configured criteria.
- **Knowledge gate for weak areas**: candidate must answer knowledge-check sufficiently.
- Knowledge-check counters (per weak area) and content-submission counters are tracked independently.
- Passing the knowledge gate does **not** skip content revision. Candidate must still submit corrected content and pass assignment criteria.
- If content still does not pass after **3 total submissions** (**initial submission + 2 resubmissions**), Agent AI escalates to Marketing Leader for intervention and final direction.
