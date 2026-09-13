# Requirements

## 1. Business Requirements

**BR-01:** The business needs employees to have access to approved and relevant HR and IT information through a centralized self-service solution.

**BR-02:** The business needs employees to obtain answers to routine HR and IT questions without requiring direct support-team assistance.

**BR-03:** The business needs employee responses to be based on approved and maintained HR and IT knowledge sources.

**BR-04:** The business needs employees to receive accurate and reliable answers to routine HR and IT questions, with a target accuracy of at least 95% during MVP testing.

**BR-05:** The business needs employee information and company knowledge to be protected through appropriate security and privacy controls before the MVP pilot.

**BR-06:** The business needs to improve productivity by enabling employees to obtain faster answers while reducing the number of repetitive requests handled by HR and IT teams.


## 2. Functional Requirements

**FR-01:** The system must allow users to ask routine HR and IT questions in natural language.

**FR-02:** The system must generate answers based on approved HR and IT knowledge sources.

**FR-03:** The system must display the reference or source used for each answer.

**FR-04:** The system must prevent users from accessing information they are not authorized to access.

**FR-05:** The system must escalate requests to the human support team when the assistant cannot provide an appropriate answer.

**FR-06:** The system must capture basic usage data required to measure agreed project KPIs, including usage, resolution, response time, and escalation metrics.


## 3. Non-Functional Requirements

**NFR-01:** The system must meet the organization's defined security requirements, with no unresolved high-severity security vulnerabilities before pilot deployment.

**NFR-02:** The system must provide responses within the agreed response-time target for the MVP.

**NFR-03:** The system must meet the agreed availability target during the pilot.

**NFR-04:** The system must achieve at least 95% accuracy when tested against the agreed set of representative HR and IT questions.

**NFR-05:** The system must protect confidential and personal information and prevent unauthorized disclosure or access.

**NFR-06:** The system must provide an intuitive and accessible user experience that enables pilot users to use the assistant with minimal training.


## 4. Acceptance Criteria

### FR-01 — Natural Language Questions

**AC-01:** Given a user has access to the AI assistant, when the user submits a routine HR or IT question in natural language, then the system must process the question and provide a response.

**AC-02:** Given a user asks a supported HR or IT question using different natural-language wording, when the question is submitted, then the system must recognize the question and provide an appropriate answer.

**AC-03:** Given a user submits a question outside the approved MVP scope, when the system cannot provide an appropriate answer, then the system must inform the user that the question is unsupported and provide the appropriate escalation path.


### FR-02 — Approved Knowledge Sources

**AC-01:** Given a user submits a question within the approved HR/IT scope, when the system generates a response, then the response must be based on information contained in an approved HR or IT knowledge source.

**AC-02:** Given a user submits a question within the approved HR/IT scope, when the system generates a response, then the response must display a reference or link to the approved knowledge source used.

**AC-03:** Given a user submits a question outside the approved MVP knowledge scope, when the system cannot provide an answer based on approved knowledge sources, then the system must clearly inform the user that the question is unsupported and provide the appropriate escalation path.


### FR-04 — Authorization

**AC-01:** Given a user attempts to access information they are not authorized to access, when the access request is submitted, then the system must block access and display an appropriate authorization message.

**AC-02:** Given a user submits a question that would require access to unauthorized information, when the system processes the request, then the system must not disclose the restricted information and must inform the user that the requested information cannot be provided.

**AC-03:** Given a user is not authorized to access a specific information source, when the user asks a question that requires information from that source, then the system must not disclose the restricted information, including directly or indirectly through the generated response.


### NFR-01 — Security

**AC-01:** Given the organization's defined security requirements, when security testing is completed before pilot deployment, then there must be no unresolved high-severity security vulnerabilities.

**AC-02:** Given a high-severity security vulnerability is identified during testing, when the vulnerability remains unresolved, then pilot deployment must be blocked until the vulnerability is remediated and successfully retested.

**AC-03:** Given a security vulnerability is identified, when the vulnerability is assessed, then it must be classified according to the organization's security severity criteria and managed according to the agreed remediation or risk-acceptance process.


### NFR-04 — Accuracy

**AC-01:** Given an agreed set of representative HR and IT questions, when the system is tested, then at least 95% of the evaluated responses must be accurate and supported by approved knowledge sources. If the accuracy is below 95%, the requirement is not met and the system must be reviewed before pilot deployment.
