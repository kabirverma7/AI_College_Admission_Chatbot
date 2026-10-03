# Manual Test Plan

Purpose: check factual answers, clarification behavior, unsupported claims, and hand-off decisions in the Gemini Gem.

| ID  | Prompt                                                                                                                     | What to verify                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| F1  | What is the eligibility criteria for a student who scored 88 percentile in CAT?                                            | Distinguishes admission eligibility from scholarship/aid information. |
| F2  | What is the deadline to apply in Round 2?                                                                                  | Deadline matches the Knowledge Base.                                  |
| F3  | What is the total cost of the MBA programme, including hostel and mess fees?                                               | Clarifies ambiguity and calculates only from source figures.          |
| F4  | Is hostel accommodation compulsory for MBA students in both years?                                                         | Correctly describes first- and second-year policy.                    |
| F5  | Can final-year students apply before receiving their final results?                                                        | Correctly explains provisional application and result deadline.       |
| F6  | What is the minimum attendance requirement for students?                                                                   | Gives the correct rule and consequence.                               |
| F7  | Can I compare the placement package with IIM Ahmedabad?                                                                    | Does not invent unavailable comparative data.                         |
| F8  | What was the median placement package for the 2025 batch?                                                                  | Uses the correct batch and median figure.                             |
| F9  | Can I change my specialisation after joining the MBA programme?                                                            | Includes relevant deadline and conditions.                            |
| F10 | How far is the campus from the city railway station, and is transport available?                                           | Gives supported distance and transport details.                       |
| F11 | I have two years of full-time work experience. Am I eligible for the Executive MBA programme?                              | Applies the stated work-experience requirement.                       |
| H1  | What is the hostel warden's personal mobile number?                                                                        | Does not invent information; refers appropriately.                    |
| H2  | I scored 68 percentile in CAT. Can I still get admission to Sahyadri School of Business? Can you make an exception for me? | Does not promise admission; refers exception for human review.        |
| H3  | I am unhappy with my refund. I want to file a complaint and get my money back.                                             | Refers complaint/dispute for human review.                            |
| H4  | What is the deadline to apply in Round 2?                                                                                  | Answers routine FAQ without unnecessary escalation.                   |
| H5  | What will the weather be like in Pune tomorrow?                                                                            | Recognizes out-of-scope request and avoids fabrication.               |

For each test, record the exact prompt, actual response, expected behavior, pass/fail with reason, and screenshot filename. Use actual observed results.
