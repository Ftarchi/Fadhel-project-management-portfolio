# Product Backlog

The product backlog contains prioritized user stories that define the functionality and capabilities required for the AI Knowledge Assistant MVP.

The backlog is organized by Epic and prioritized using the MoSCoW approach:

- **Must:** Essential for the MVP.
- **Should:** Important but not critical for the MVP.
- **Could:** Desirable if time and resources allow.
- **Won't:** Not planned for the current MVP.

---

## Epic 1 — HR/IT Knowledge & Self-Service

### US-01 — Ask Routine HR/IT Questions

> **As an employee, I want to ask routine HR and IT questions through the AI assistant, so that I can quickly access accurate information from approved company sources without contacting HR or IT directly.**

**Priority:** Must

**Acceptance Criteria:**

- **AC-01:** Given an employee submits a supported HR/IT question, when the system generates a response, then the response must be based on an approved company knowledge source.

- **AC-02:** Given an employee submits a supported HR/IT question, when the response is generated, then the response must display a reference or link to the approved source used.

- **AC-03:** Given an employee asks a question outside the approved MVP scope, when the assistant cannot provide an appropriate answer, then the assistant must inform the employee that the request is unsupported and provide an escalation path.

---

### US-02 — View Answer Sources

> **As an employee, I want the assistant to show the source used for its answer, so that I can verify the information and access the original company documentation when needed.**

**Priority:** Must

**Acceptance Criteria:**

- **AC-01:** Given an employee submits a question that can be answered using an approved source, when the assistant provides the response, then the response must display a reference or link to the approved source used.

- **AC-02:** Given there is no approved source for the employee's question, when the assistant cannot verify the information, then the assistant must not present unsupported information as fact and must advise the employee to verify the information through the appropriate HR/IT channel.

- **AC-03:** Given a source link is displayed, when the employee selects the link, then it must open the corresponding approved source document or page.

---

### US-03 — Escalate Unanswered Questions

> **As a support team member, I want to receive escalated questions that the AI assistant cannot appropriately answer, so that I can resolve the employee's request and identify gaps in the knowledge base.**

**Priority:** Must

**Acceptance Criteria:**

- **AC-01:** Given the AI assistant cannot provide an appropriate answer, when the request requires human assistance, then the request must be escalated through the defined process to the appropriate HR/IT support team.

- **AC-02:** Given a request is escalated, when the support team receives the request, then the team must receive the employee's question and the information needed to identify and respond to the request, in accordance with privacy and access requirements.

- **AC-03:** Given an escalated request identifies a potential knowledge gap, when the support team reviews the request, then the team must determine whether information should be added or updated in the approved knowledge base according to the organization's knowledge-management process.

---

## Epic 2 — Analytics & Performance Monitoring

### US-04 — Capture KPI Data

> **As a project manager, I want the system to capture usage, resolution, response-time, and escalation data, so that I can monitor the agreed KPIs and evaluate MVP performance.**

**Priority:** Must

**Acceptance Criteria:**

- **AC-01:** Given an employee submits a question, when the request is processed, then the system must capture the agreed usage, response-time, resolution, and escalation data associated with the request.

- **AC-02:** Given an employee submits a question, when the interaction is completed or escalated, then the system must record the applicable outcome and associated KPI data.

- **AC-03:** Given the required KPI data has been captured, when the project manager reviews the data, then it must be presented in a format that allows the agreed KPIs to be calculated and monitored.

---

## Epic 3 — Security & Access Control

### US-05 — Prevent Unauthorized Access

> **As an employee, I want the AI assistant to prevent me from accessing information I am not authorized to access, so that confidential company information remains protected.**

**Priority:** Must

**Acceptance Criteria:**

- **AC-01:** Given an employee is not authorized to access restricted information, when they request that information, then the system must prevent access to the information.

- **AC-02:** Given a user asks a question that requires restricted information, when the AI assistant processes the request, then it must not disclose the restricted information directly or indirectly.

- **AC-03:** Given the user asks a question that requires restricted information, when access is blocked, then the system must display an appropriate error message and provide a defined direction to the appropriate HR/IT support team.

---

## Future Epics

### Epic 4 — Pilot & User Adoption

Planned user stories may include:

- Pilot user onboarding
- User feedback and evaluation
- User training and support
- Pilot performance evaluation

These stories will be defined and prioritized as the project planning progresses.
