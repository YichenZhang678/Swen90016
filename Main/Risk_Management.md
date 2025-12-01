# Risk Management Strategy - Urban Tree Explorer Project

## Risk Assessment Framework

Each identified risk includes the following details:

- **Risk Statement:** Description of the risk, structured as:
  **Action → Consequence → Impact**
- **Probability:** Likelihood of occurrence (0-99.9%)
- **Impact:** Severity if the risk materializes (scale of 0-10)
- **Exposure:** Probability × Impact
- **Response Strategy:** Approach to handle the risk (Accept / Ignore / Mitigate / Avoid)
- **Mitigation Plan:** Detailed approach to address the risk (if applicable)I'll analyze each risk's probability and impact ratings:


## Project Risks

### Risk ID: R-001

**Risk Statement:**
_"Inadequate experience with WordPress development → Delays in implementing core features → Failure to meet Sprint 1 deliverables (interactive map and 2FA)"_

- **Probability:** 75.0%, team has indicated limited WordPress experience and it's a specialized skill
- **Impact:** 9, directly affects core deliverables in Sprint 1 (map and 2FA) which are fundamental features
- **Exposure:** 75.0% × 9 = **6.75**
- **Mitigation Strategy:** **Mitigate**
- **Mitigation Plan:**
  - Allocate time at the beginning of Sprint 1 for team members to complete WordPress tutorials
  - Assign team members with prior WordPress experience to lead critical components
  - Schedule knowledge-sharing sessions within the team to ensure all members understand the technology stack
  - Create a technical documentation repository for common issues and solutions
  - Identify WordPress plugins specifically designed for map visualization to simplify implementation

### Risk ID: R-002

**Risk Statement:**
_"Issues with the City of Melbourne tree dataset → Incomplete or inaccurate data visualization → Poor user experience and reduced functionality"_

- **Probability:** 35.0%, City of Melbourne data is officially maintained and generally reliable
- **Impact:** 7, as data quality directly affects the core map visualization feature
- Impact isn't maximum because workarounds exist for incomplete data
- **Exposure:** 35.0% × 7 = **2.45**
- **Mitigation Strategy:** **Mitigate**
- **Mitigation Plan:**
  - Perform early data validation and cleaning before integration
  - Implement error handling for missing or inconsistent data points
  - Create a data preprocessing pipeline to standardize the dataset format
  - Develop fallback visualization options for areas with incomplete data
  - Document any data limitations for transparency to users

### Risk ID: R-003

**Risk Statement:**
_"Limited team availability due to competing coursework → Reduced development hours → Incomplete deliverables and poor code quality"_

- **Probability:** 50.0%, as competing coursework is a common challenge but can be managed
- **Impact:** 5, while it affects development time, it can be mitigated through proper planning, Team can adjust workload and priorities to handle this common situation
- **Exposure:** 50.0% × 5 = **2.5**
- **Mitigation Strategy:** **Mitigate**
- **Mitigation Plan:**
  - Create a detailed team schedule at the start of the project accounting for other course deadlines
  - Break down tasks into smaller, manageable units that can be completed in shorter time blocks
  - Implement pair programming for critical features to improve code quality and knowledge sharing
  - Schedule regular check-ins twice a week to ensure progress is maintained
  - Prioritize core requirements over nice-to-have features

### Risk ID: R-004

**Risk Statement:**
_"Challenges implementing secure 2-factor authentication → Security vulnerabilities or non-functional authentication → Failure to meet Sprint 1 security requirements"_

- **Probability:** 55.0%, due to complexity of security implementations
- **Impact:** 8, security features are critical and cannot be compromised
- **Exposure:** 55.0% × 8 = **4.4**
- **Mitigation Strategy:** **Mitigate**
- **Mitigation Plan:**
  - Research and select a well-maintained WordPress 2FA plugin with good documentation
  - Allocate additional time for security testing of the authentication system
  - Create a comprehensive test plan for authentication scenarios
  - Seek guidance from the teaching team on recommended 2FA approaches for WordPress
  - Implement a fallback authentication method if primary 2FA approach encounters issues

### Risk ID: R-005

**Risk Statement:**
_"Changes to requirements for Sprints 2 and 3 → Rework of existing features → Project delays and scope creep"_

- **Probability:** 80.0%, requirement changes are almost certain in agile development
- **Impact:** 6, changes are expected and can be managed with proper planning
- **Exposure:** 80.0% × 6 = **4.8**
- **Mitigation Strategy:** **Accept**
- **Contingency Plan:**
  - Design Sprint 1 deliverables with modularity in mind to accommodate future changes
  - Document all assumptions made during development to facilitate easier adaptation
  - Maintain clean code practices to make future modifications less challenging
  - Reserve buffer time in Sprint 2 and 3 planning to accommodate requirement changes
  - Regularly communicate with teaching staff to get early insights into potential requirement changes


### Risk ID: R-006 

**Risk Statement:**  
Expected moderate learning curve for WordPress → Server instability and limited plugin compatibility → Delays in feature implementation 

- **Probability:** 40.0%, based on WordPress's known learning curve
- **Impact:** 10, server stability is crucial for entire application
- **Exposure:** 40.0% × 10 = **4**
- **Mitigation Strategy:** **Mitigate**

- **Contingency Plan**
  - Implement server setting optimizations
  - compormise on data scale and focus on feature implementation



### Risk ID: R-007 

**Risk Statement:**  
Server access issues → Unable to deploy and test changes → Project timeline delays

- **Probability:** 10.0%, server access is typically reliable
- **Impact:** 6, delays are significant but temporary
- **Exposure:** 10.0% × 6 = **0.6**
- **Mitigation Strategy:** **Accept**

- **Contingency Plan**
  - Escalate to IT Services for investigation
  - Extended project deadline to accommodate delay


### Risk ID: R-008 

**Risk Statement:**  
Rating functionality returning 500 internal server error → Rating data cannot be sent to backend → Average scores cannot be calculated or displayed

- **Probability:** 10.0%, most server errors can be debugged with time
- **Impact:** 15, rating functionality is a core feature
- **Exposure:** 10.0% × 15 = **1.5**
- **Mitigation Strategy:** **Mitigate**

- **Contingency Plan**
  - Identify issue source
  - Contacted plugin developers for technical support
  - Implement static information display as temporary workaround

### Risk ID: R-009 
**Risk Statement:**  
WordPress Go Map documentation requires iframe plugin for YouTube video embedding → Missing plugin prevents video integration → Feature implementation blocked

- **Probability:** 40.0%, plugin dependencies can change frequently
- **Impact:** 3, video integration is important for documentation
- **Exposure:** 40.0% × 3 = **1.2**
- **Mitigation Strategy:** **Mitigate**
- **Contingency Plan**
  - Escalate issue to teaching team
  - contact plugin developer



## Risk Tracking Table

| **Risk ID** | **Risk Statement (Summary)**                          | **Probability (%)** | **Impact (0-10)** | **Exposure** | **Strategy** |
| ----------- | ----------------------------------------------------- | ------------------- | ----------------- | ------------ | ------------ |
| R-001       | Inadequate WordPress experience impacts development   | 75.0%               | 9                 | 6.75         | Mitigate 🟡  |
| R-002       | Dataset issues affect visualization quality           | 35.0%               | 7                 | 2.45         | Mitigate 🟡  |
| R-003       | Limited team availability due to competing coursework | 50.0%               | 5                 | 2.5          | Mitigate 🟡  |
| R-004       | 2FA implementation challenges                         | 55.0%               | 8                 | 4.4          | Mitigate 🟡  |
| R-005       | Changing requirements for future sprints              | 80.0%               | 6                 | 4.8          | Accept 🟢    |
| R-006       | WordPress learning curve affects server stability     | 40.0%               | 10                | 4.0          | Mitigate 🟡  |
| R-007       | Server access issues delay project                    | 10.0%               | 6                 | 0.6          | Accept 🟢    |
| R-008       | Rating functionality returning server errors          | 10.0%               | 15                | 1.5          | Mitigate 🟡  |
| R-009       | iframe plugin issues block video integration         | 40.0%               | 3                | 4.0          | Mitigate 🟡  |

## Legend for Mitigation Strategies

- **Accept** 🟢 → Acknowledge the risk but take no preventive action; contingency plan prepared
- **Ignore** 🔵 → Considered low priority with minimal impact
- **Mitigate** 🟡 → Take action to reduce probability or impact
- **Avoid** 🔴 → Change project approach to eliminate the risk

This risk management strategy will be continuously reviewed and updated throughout the project lifecycle, with particular attention during sprint planning and retrospectives to ensure risks are being effectively managed.
