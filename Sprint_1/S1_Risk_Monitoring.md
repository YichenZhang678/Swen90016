# 📊 Project Risk Monitoring – Sprint 1 (Urban Tree Explorer)

Risk monitoring was conducted continuously during Sprint 1 through Scrum ceremonies including Sprint Planning, Daily Stand-ups, Sprint Review, and Sprint Retrospective. Two risks fully materialized and one was officially resolved due to a project requirement change.

---

## ✅ Risk Monitoring Summary

| Risk ID | Risk Statement Summary                            | Status                         | Actions Taken                                                                | Lessons Learned                                         |
| ------- | ------------------------------------------------- | ------------------------------ | ---------------------------------------------------------------------------- | ------------------------------------------------------- |
| R-004   | Difficulty implementing secure 2FA authentication | Resolved (Requirement Dropped) | 2FA development cancelled following official instructions from teaching team | Confirm feature scope with client/stakeholder regularly |
| R-005   | Requirement changes cause rework and delays       | Materialized                   | Adjusted backlog and shifted developer focus to updated requirements         | Validate requirements mid-sprint to avoid waste         |
| R-006   | WordPress server limitations delay development    | Materialized                   | Attempted plugin alternatives, raised issue to teaching staff, shifted focus | Validate environments early and escalate blockers       |

---

## 🧩 Risk Monitoring via Scrum Ceremonies

| Scrum Ceremony           | Risk Monitoring Activities                                                                                     |
| ------------------------ | -------------------------------------------------------------------------------------------------------------- |
| **Sprint Planning**      | Removed login and 2FA stories after teaching update; reassigned developer time to focus on core functionality. |
| **Daily Stand-Ups**      | Discussed requirement and environment-related blockers and coordinated task reassignment.                      |
| **Sprint Review**        | Reflected scope changes in deliverables; explained removal of features like login and 2FA.                     |
| **Sprint Retrospective** | Identified the need to confirm scope mid-sprint and monitor platform/environment limitations early on.         |

---

## 🟢 Resolved Risk: R-004 – 2FA Development

**Risk Statement:**  
Implementing secure two-factor authentication → Security vulnerabilities or non-functional login system → Failure to meet Sprint 1 requirements

- **Status:** Resolved – Requirement officially dropped
- **Action Taken:**
  - Removed 2FA-related tasks from Sprint Backlog
  - Redirected backend effort toward core feature development
  - Preserved partial 2FA work in a separate Git branch for future use
- **Lesson Learned:**  
  Stakeholder priorities may shift during the sprint. Always monitor official communications for requirement updates.

---

## 🟠 Materialized Risk: R-005 – Requirement Change Mid-Sprint

**Risk Statement:**  
Requirement changes mid-sprint → Feature rework or replacement → Development delays and scope misalignment

- **Status:** Materialized
- **Impact:**  
  - Login page was deprioritized
  - Map interaction requirements were modified mid-sprint
- **Action Taken:**
  - Conducted backlog refinement session
  - Removed deprecated tasks and updated user stories
  - Communicated changes across the team and updated documentation
- **Lesson Learned:**  
  Introduce mid-sprint requirement validation checkpoints to reduce rework and ensure delivery alignment.

---

## 🔴 Materialized Risk: R-006 – WordPress Server Environment Limitations

**Risk Statement:**  
Expected moderate learning curve for WordPress → Server instability and limited plugin compatibility → Delays in feature implementation and lack of debugging support

- **Status:** Materialized
- **Impact:**  
  - WordPress server was inconsistent, affecting deployment and testing  
  - Map rendering could not be completed due to plugin/environment limitations  
  - Debugging was ineffective due to restricted platform access
- **Action Taken:**
  - Tested alternative plugins and fallback implementations  
  - Reported environment limitations to the teaching team  
  - Temporarily shifted focus to front-end design and data preparation
- **Lesson Learned:**  
  Validate critical platforms and tools early. Raise environment-related blockers promptly and plan for contingency pathways.

---

## 📘 Notes

- These risk updates reflect guidance from the SWEN90016 teaching team.
- All backlog changes and task removals were tracked via Git and documented in the project management tools.
