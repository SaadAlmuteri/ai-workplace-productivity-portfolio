# Section 1b: Before & After Prompt Comparison

## 1. Before (Weak Prompt)
> *"Write an email to my team telling them the sprint meeting is moved and they need to bring their updates."*

### Initial Result
> *Hey everyone, the sprint meeting is moved to another time. Please make sure you bring all your updates with you so we can discuss them. Thanks!*

## 2. After (Improved Prompt using C.A.R.E. Framework)
> **Role:** Technical Project Coordinator.  
> **Context:** The weekly Sprint Review meeting is rescheduled from Wednesday 10:00 AM to Thursday 2:00 PM due to system maintenance.  
> **Action:** Draft a concise, professional notification email to the engineering and QA teams.  
> **Expected Output:** Professional email including: new meeting date/time, agenda items to prepare (completed tickets, blockers, demo links), and a reminder to update Jira boards by Thursday 11:00 AM.

### Improved Result
> **Subject:** RESCHEDULED: Weekly Sprint Review — Thursday @ 2:00 PM  
> 
> **Hi Team,**  
> 
> Please note that this week's **Sprint Review & Demo** has been rescheduled due to planned server maintenance on Wednesday morning.  
> 
> **New Meeting Details:**  
> - **Date & Time:** Thursday, October 15, 2026 | 2:00 PM – 3:00 PM  
> - **Location:** Virtual Meeting Room 3  
> 
> **Action Items Before the Meeting:**  
> 1. **Update Jira:** Ensure all active sprint user stories are updated by **Thursday @ 11:00 AM**.  
> 2. **Demos Ready:** Prepare 2-minute live walkthrough links for closed backlog items.  
> 3. **Blockers Logged:** Document any active third-party dependencies in the sprint board.  
> 
> Thank you for your flexibility.  
> 
> Best regards,  
> **Saad Nasser Al-Mutairi**  
> *Project Coordinator*

## 3. What Improved?
- **Clarity & Actionability:** Specified exact dates, times, and deadlines rather than vague instructions.
- **Clear Operational Expectations:** Replaced "bring updates" with concrete deliverables (Jira updates, demo links, blocker logs).
- **Professional Formatting:** Utilized bold labels and bulleted lists to allow team members to scan requirements in seconds.
- **Contextual Alignment:** Clarified the reason for the rescheduling (server maintenance), preventing confusion.
