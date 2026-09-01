# Section 1a: Workplace Prompt Library

**Role Scenario:** Project Coordinator  
**Frameworks Used:** C.A.R.E. & R.C.T.O. 

## Reusable Prompts Matrix

| Prompt Name | Workplace Task | Framework | Prompt Structure | Expected Output Format |
|---|---|---|---|---|
| **Schedule Delay Alert** | Communicating milestone delays to management | **C.A.R.E.** | **Context:** Project Alpha is delayed by 4 days due to vendor API integration backlog.<br>**Action:** Draft a diplomatic, proactive update email.<br>**Role:** Senior Project Coordinator.<br>**Expected Output:** Formal 3-paragraph email with reason, mitigation plan, and revised timeline. | 3-paragraph executive email with clear bullet points. |
| **Action-Item Extractor** | Parsing unorganized meeting transcripts | **R.C.T.O.** | **Role:** Project Management Officer.<br>**Context:** 45-minute sprint sync transcript.<br>**Task:** Extract decisions and action items. If an owner/date is missing, mark as `[Not Specified]`.<br>**Output:** Markdown table (Task, Owner, Deadline, Priority). | Structured Markdown table with 4 columns. |
| **Executive Status Brief** | Summarizing bi-weekly progress for leadership | **C.A.R.E.** | **Context:** Multiple workstreams completed user testing and database migration.<br>**Action:** Synthesize accomplishments and open blockers.<br>**Role:** Technical Project Coordinator.<br>**Expected Output:** Bulleted executive summary under 150 words. | High-level summary followed by 3 core metric bullets. |
| **Risk Register Categorizer** | Classifying project risks into severity tiers | **Few-Shot / R.C.T.O.** | **Role:** Risk Management Specialist.<br>**Context:** Project launch checklist.<br>**Task:** Categorize submitted risks based on provided examples (High/Med/Low impact).<br>**Output:** Risk Register table with mitigation triggers. | 4-column risk evaluation table. |
| **Vendor SLA Follow-up** | Inquiring about pending hardware/service delivery | **C.A.R.E.** | **Context:** Hardware vendor missed the initial delivery SLA by 48 hours.<br>**Action:** Write a firm yet collaborative follow-up inquiry.<br>**Role:** Operations Coordinator.<br>**Expected Output:** Professional inquiry email referencing SLA clauses. | 2-paragraph professional correspondence. |
| **Sprint Retrospective Framework** | Structuring sprint retrospective discussions | **R.C.T.O.** | **Role:** Agile Project Coordinator.<br>**Context:** Team completed Sprint 14 with minor deployment bottlenecks.<br>**Task:** Generate 4 targeted discussion questions for the retro session.<br>**Output:** 4 distinct questions categorized by (What went well, What didn't, Actions). | Numbered list categorized by retro themes. |

## Example Outputs

### Example 1: Schedule Delay Alert (C.A.R.E.)
**Generated Output:**
> **Subject:** Project Alpha — Schedule Adjustment & Mitigation Plan  
> **Dear Steering Committee,**  
> 
> I am writing to provide an update regarding the integration milestone for Project Alpha. Due to unexpected technical dependencies during the third-party API integration, the delivery milestone has been shifted by 4 business days, moving our target completion date to **October 18, 2026**.  
> 
> To mitigate further schedule impact, the technical team has allocated additional engineering capacity to parallel-track UI testing while backend endpoints are finalized.  
> 
> We remain on track for the overall quarterly launch. Please let me know if you require further technical breakdowns during Thursday’s sync.  
> 
> Best regards,  
> **Saad Nasser Al-Mutairi**  
> *Project Coordinator*

### Example 2: Action-Item Extractor (R.C.T.O.)
**Generated Output:**

| Task | Owner | Deadline | Priority |
|---|---|---|---|
| Complete API security validation | Sarah Al-Otaibi | Oct 12, 2026 | High |
| Prepare training user manual | Saad Nasser | Oct 15, 2026 | Medium |
| Procure backup cloud storage quota | `[Not Specified]` | `[Not Specified]` | Low |
