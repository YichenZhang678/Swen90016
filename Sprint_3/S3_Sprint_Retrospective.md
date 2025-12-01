# 🚀 Sprint Retrospective – Assignment 2

A Sprint Retrospective is a structured discussion where the team reflects on the past sprint to improve future performance. It focuses on successes, challenges, and actionable improvements. This retrospective was conducted immediately after Sprint 3 to capture insights before the final submission stage.

## Overview

| Category                | Details                                                                                              |
| ----------------------- | ---------------------------------------------------------------------------------------------------- |
| **Meeting Facilitator** | Scrum Master                                                                                         |
| **Goal of the Meeting** | Reflect on sprint successes and challenges, and identify actionable improvements for future sprints. |
| **Attendees**           | Development Team, Scrum Master, Product Owner                                                        |

## What Went Well

- ✅ **Full Feature Delivery**: All core functionalities, including Page 4 (map-based view) and Page 5 (category visualization), were fully implemented and tested by the end of the sprint. The application reached feature completeness.

- ✅ **Thorough QA and Debugging**: Multiple rounds of QA ensured all modules operated correctly. The use of structured testing improved the quality and stability of the product.

- ✅ **Balanced Documentation Ownership**: Each team member was assigned sprint documentation (e.g., Risk Monitoring, Stand-Up, Retrospective), allowing fair distribution of final writing tasks and stronger accountability.

- ✅ **Consistent Communication**: From development to documentation, team members communicated progress daily, allowing fast issue resolution and eliminating ambiguity around task status.

## What Could Have Been Done Better

- ⏳ **Late Start on Documentation**

  Although documentation responsibilities were clearly assigned, several team members only began drafting near the end of the sprint. This created unnecessary pressure and reduced time for peer review. Earlier writing alongside development would have allowed more iterations.

- ⏳ **UI Inconsistencies Between Pages**

  Despite overall polish, small design inconsistencies (e.g., padding, font sizes) persisted between Page 4 and Page 5. These could have been prevented by defining a shared UI style reference earlier in the sprint.

- ⏳ **Documentation Overlap and Redundancy**

  A few content areas (e.g., testing procedures and sprint goals) were repeated across different files like QA and Backlog. Without cross-review until the end, this led to minor duplication.

- ⏳ **Rating System Bug**

  During integration and user testing, a bug was discovered in the rating feature, causing display and interaction inconsistencies. The issue likely stemmed from desynchronized frontend component states or delayed backend response handling. Although the problem was eventually bypassed or patched, it highlighted the lack of sufficient integration-level testing and revealed the need for more comprehensive regression tests at the system level.

## What We Will Do Differently

- ⏳ **Early Documentation Drafting**: Team members will begin drafting documentation as soon as related development tasks are completed to allow enough time for editing and feedback.

- ⏳ **Shared Design System**: Before interface building, the team will agree on shared UI values (margins, font styles, spacing) to ensure consistency across all pages.

- ⏳ **Inter-Doc Review Process**: Before final submission, members will exchange and review each other’s files to avoid redundant or conflicting content.

- ⏳ **Real-Time UI Check-in**: Developers will demo UI progress mid-sprint to allow live feedback on layout and interactions across screens.

- ⏳ **Track Sprint Load Balance**: Continue to monitor documentation and implementation loads to ensure all team members have clearly scoped and manageable tasks.

- ⏳ **System-Level Regression Testing**: After feature completion, a full regression test should be conducted—especially for components involving cross-module interactions—to prevent late-stage bugs like the rating issue.

## Actionable Items for Next Sprint

| Action Item                                                  | Owner         | Due Date | Status      |
| ------------------------------------------------------------ | ------------- | -------- | ----------- |
| Begin documentation drafts immediately after implementation  | All Members   | N/A      | ✅ Completed |
| Establish shared style references for UI layout              | UI Lead       | N/A      | ✅ Completed |
| Conduct inter-document reviews to remove redundancy          | All Members   | N/A      | ✅ Completed |
| Include mid-sprint UI alignment session                      | Dev Team      | N/A      | ✅ Completed |
| Distribute final documentation tasks with clear scope        | Scrum Master  | N/A      | ✅ Completed |
| Conduct system-wide regression test including rating feature | QA & Dev Team | N/A      | ✅ Completed |

## Conclusion

Sprint 3 marked the final phase of this project, culminating in both feature completion and full documentation delivery. While overall execution was strong, we identified areas for earlier alignment—especially in UI and documentation workflows. The discovery of the rating bug reaffirmed the need for thorough system-level testing. These lessons will be instrumental in improving efficiency, consistency, and delivery confidence in future agile development efforts.
