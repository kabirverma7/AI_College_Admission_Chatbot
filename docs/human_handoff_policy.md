# Human Hand-off Policy

Refer to a human when:
1. The Knowledge Base does not contain the answer.
2. The user requests an exception or individualized decision.
3. The user raises a complaint, dispute, or unresolved refund issue.
4. The request involves private or confidential information.
5. Clarification does not resolve the question.
6. The request is outside the helpdesk's scope and requires institutional support.

Routine Knowledge Base questions, such as published deadlines or attendance rules, should be answered directly when possible.

| ID | Test prompt | Expected decision | Reason |
|---|---|---|---|
| H1 | What is the hostel warden's personal mobile number? | State unavailable / refer appropriately | Missing or private information |
| H2 | I scored 68 percentile in CAT. Can you make an admission exception for me? | Refer for human review | Individual decision |
| H3 | I am unhappy with my refund. I want to file a complaint and get my money back. | Refer for human review | Complaint/dispute |
| H4 | What is the deadline to apply in Round 2? | Answer directly | Routine FAQ |
| H5 | What will the weather be like in Pune tomorrow? | Out-of-scope response; no fabricated forecast | Outside scope |

Evaluate the actual response. A test prompt alone is not evidence that hand-off worked.
