# 📊 Project Risk Monitoring – Sprint 3 (Urban Tree Explorer)

Risk monitoring was conducted continuously during Sprint 3 through Scrum ceremonies including Sprint Planning, Daily Stand-ups, Sprint Review, and Sprint Retrospective. Two risks were identified and tracked, with one successfully resolved through teaching team intervention and one remaining unresolved pending external support.

---

## ✅ Risk Monitoring Summary

| Risk ID | Risk Statement Summary | Status | Actions Taken | Lessons Learned |
| ------- | -------------------- | ------ | ------------- | --------------- |
| R-008 | Rating functionality returning 500 internal server error | Materialized | - Identified as plugin-related issue<br>- Contacted plugin developers<br>- Implemented static display as workaround | Allocate buffer time for external dependency issues and plan alternative deliverables when third-party support is uncertain |
| R-009 | Missing iframe plugin preventing YouTube video embedding | Resolved | - Escalated to teaching team<br>- Teaching team contacted plugin company<br>- Plugin access granted | Establish clear escalation protocols and identify stakeholder networks early in sprint planning |

---

## 🧩 Risk Monitoring via Scrum Ceremonies

| Scrum Ceremony | Risk Monitoring Activities |
| -------------- | ------------------------- |
| **Sprint Planning** | Identified potential rating functionality issues and YouTube embedding limitations |
| **Daily Stand-Ups** | Tracked progress on plugin developer contact and iframe plugin availability |
| **Sprint Review** | Reported on rating functionality workaround implementation and iframe plugin resolution |
| **Sprint Retrospective** | - Discussed need for early external dependency identification<br>- Reviewed escalation pathways for plugin access<br>- Planned contingency approaches for third-party integrations |

---

## 🔴 Materialized Risk: R-008 – Rating Functionality Server Error

**Risk Statement:**  
Rating functionality returning 500 internal server error → Rating data cannot be sent to backend → Average scores cannot be calculated or displayed

- **Status:** materialized
- **Current Impact:**  
 - Radio button clicks trigger 500 internal server errors consistently
 - Rating data not transmitted to backend server
 - Average score calculation and display functionality compromised
- **Actions Taken:**
 - Identified issue as plugin-related problem
 - Contacted plugin developers for technical support
 - Implemented static information display as temporary workaround
- **Current State:**  
 No response received from plugin developers. Feature remains non-functional with static display serving as interim solution.
- **Lesson Learned:**  
 Include sprint buffer time for external dependency risks and define minimum viable deliverables when third-party support response times are uncertain.

---

## 🟢 Resolved Risk: R-009 – Missing Iframe Plugin for YouTube Embedding

**Risk Statement:**  
WordPress Go Map documentation requires iframe plugin for YouTube video embedding → Missing plugin prevents video integration → Feature implementation blocked

- **Status:** Resolved
- **Original Impact:**  
 - YouTube links could not be added to tree descriptions
 - Video embedding functionality unavailable
 - Feature development blocked pending plugin access
- **Resolution Actions:**
 - Escalated issue to SWEN90016 teaching team
 - Teaching team contacted plugin company directly
 - Iframe plugin access successfully granted
- **Outcome:**  
 Plugin now available and YouTube video embedding functionality restored, allowing for enhanced tree information display.
- **Lesson Learned:**  
 Map stakeholder escalation paths during sprint planning and establish clear communication protocols to expedite external blockers resolution.

---

## 📘 Notes

- These risk updates reflect guidance from the SWEN90016 teaching team.
- Rating functionality remains a critical dependency on external plugin support.
- All workarounds and plugin installations were tracked via Git and documented in project management tools.