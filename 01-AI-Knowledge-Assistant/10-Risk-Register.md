# Risk Register

The risk register identifies and tracks potential events that could affect the AI Knowledge Assistant MVP. Risks are assessed based on probability and impact, with response strategies defined to reduce or manage potential effects on the project.

## Risk Scoring

Risk score is calculated as:

**Risk Score = Probability × Impact**

| Score | Priority |
|---:|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–16 | High |
| 17–25 | Very High |

---

## Risk Assessment

| ID | Risk | Probability | Impact | Score | Priority | Response |
|---|---|---:|---:|---:|---|---|
| R-01 | Outdated or inaccurate HR information may result in incorrect AI responses. | 4 | 4 | 16 | High | Mitigate |
| R-02 | Authentication/access-control integration may take longer than planned. | 3 | 5 | 15 | High | Mitigate |
| R-03 | The AI assistant may allow unauthorized access to restricted information. | 3 | 5 | 15 | High | Mitigate |
| R-04 | Schedule pressure may reduce the time available for testing and remediation. | 3 | 4 | 12 | High | Accept |
| R-05 | Limited team AI/technical experience may cause technical challenges. | 3 | 5 | 15 | High | Mitigate |

---

## Detailed Risk Responses

### R-01 — Outdated or Inaccurate HR Information

**Risk Owner:** HR Knowledge Owner / HR Manager

**Trigger:** HR knowledge sources have not been reviewed or updated within the agreed review period.

**Response Strategy:** Mitigate

**Response Action:**  
Coordinate with HR Knowledge Owners to review, validate, and approve HR knowledge sources before they are made available to the AI assistant. Establish a process for reviewing and updating the sources during the project and before pilot deployment.

---

### R-02 — Authentication/Access-Control Integration Delay

**Risk Owner:** Engineering Manager

**Trigger:** The dependent IT team has not provided a committed delivery date by the agreed milestone.

**Response Strategy:** Mitigate

**Response Action:**  
Coordinate with the dependent IT team to confirm integration requirements, dependencies, resource availability, and a committed delivery date. Track the dependency closely and escalate if the commitment cannot be secured or the date threatens the critical path.

---

### R-03 — Unauthorized Access to Restricted Information

**Risk Owner:** Security Manager

**Trigger:** Access-control testing identifies that a user can access information outside their authorized permissions.

**Response Strategy:** Mitigate

**Response Action:**  
Collaborate with Security and Engineering to implement and validate role-based access controls and least-privilege permissions, followed by security testing before pilot deployment.

---

### R-04 — Schedule Pressure Affecting Testing and Remediation

**Risk Owner:** Project Manager

**Trigger:** Schedule variance or critical-path delay reduces the available time for planned testing or remediation activities.

**Response Strategy:** Accept

**Response Action:**  
Monitor schedule progress, critical-path activities, and testing time throughout the project; reassess the risk if schedule variance threatens testing or remediation activities.

---

### R-05 — Limited AI/Technical Experience

**Risk Owner:** Project Manager

**Trigger:** Planned configuration or development activities are delayed due to gaps in the team's AI/technical expertise.

**Response Strategy:** Mitigate

**Response Action:**  
Coordinate targeted AI/technical training and coaching for the project team, and involve experienced technical resources where needed to reduce the likelihood and impact of technical challenges.

---

## Risk Monitoring and Review

The project manager will review the risk register regularly during project status meetings and update probability, impact, response actions, ownership, and triggers as the project progresses.

High-priority risks will receive increased monitoring, particularly risks that could affect the critical path, security validation, pilot readiness, or project objectives.

Risk responses will be reassessed when:

- A defined risk trigger occurs.
- Project scope changes.
- Schedule or critical-path performance changes.
- New dependencies are identified.
- Security or testing results introduce new concerns.
- The probability or impact of an existing risk changes.

Where a risk exceeds the project team's authority or requires management prioritization or decision-making, it will be escalated to the appropriate stakeholder or sponsor.

## Risk Prioritization

The project manager will prioritize risk monitoring based not only on risk score but also on:

- Potential impact on project objectives.
- Proximity of the risk.
- Critical-path impact.
- Potential to block the security or pilot readiness gate.
- Ability of the project team to control or influence the risk.
- Time available to respond if the risk occurs.
