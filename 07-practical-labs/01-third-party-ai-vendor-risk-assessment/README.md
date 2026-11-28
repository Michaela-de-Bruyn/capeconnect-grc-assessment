# Lab 01 — Third-Party AI Vendor Risk Assessment

**Portfolio:** CapeConnect AI Assurance Hub  
**Role:** Simulated GRC Analyst  
**Exercise type:** Third-party risk assessment  
**Status:** Ready for learner completion  
**Environment:** Fictional South African organisation

## 1. Learning objectives

By completing this exercise, you should be able to:
- Explain why organisations assess third-party technology providers.
- Identify information assets and data flows involving a supplier.
- Identify security, privacy, operational and contractual risks.
- Request and evaluate supplier evidence.
- Record risks using a consistent likelihood and impact method.
- Recommend proportionate risk treatment and follow-up actions.

## 2. Scenario

CapeConnect (Pty) Ltd is a fictional Cape Town-based customer support business. It plans to introduce a third-party AI chatbot to answer customer enquiries.

The chatbot may process customer names and email addresses, account-related enquiries, support conversation histories and information customers include in free-text messages.

The proposed supplier hosts the chatbot platform and provides the underlying AI model. CapeConnect remains responsible for assessing the risks associated with using the service and handling personal information.

## 3. Simulated supplier information

The following statements are fictional exercise inputs. Treat them as supplier statements, not verified facts.

| ID | Supplier statement | Initial GRC interpretation |
|---|---|---|
| S-01 | Customer prompts may be retained for up to 90 days for service improvement. | Clarify retention purpose, deletion process and whether prompts are used to train or improve models. |
| S-02 | Data is encrypted in transit. | Request details of encryption at rest, key management and supporting evidence. |
| S-03 | Multi-factor authentication is available for administrator accounts. | Confirm whether MFA is mandatory for all privileged users and how exceptions are managed. |
| S-04 | The supplier uses additional cloud and analytics subprocessors. | Request a complete subprocessor list, locations, services and change-notification process. |
| S-05 | The supplier has not yet provided its latest independent assurance report. | Request a current SOC 2 Type II report or equivalent independent assurance evidence, including scope and exceptions. |
| S-06 | The supplier says it can delete customer data when the contract ends. | Request contractual deletion commitments, timelines, backup handling and deletion confirmation. |

## 4. Your assignment

Act as the GRC Analyst supporting the proposed supplier onboarding.

### Task A — Understand the data and service

Document what personal and business information the chatbot will process, which parties will access or process it, where data could be stored or transferred, and which details remain unknown.

**Deliverable:** A short data-flow summary and a list of assumptions.

### Task B — Identify and score risks

Create at least five risks. Include privacy and data retention, privileged access and authentication, supplier/subprocessor oversight, independent assurance and control evidence, and data deletion/contract termination.

| Field | What to document |
|---|---|
| Risk ID | Unique identifier, e.g. CC-VR-001 |
| Risk statement | Cause, uncertain event and business impact |
| Asset/process | What could be affected |
| Existing control | What the supplier says is already in place |
| Evidence status | Verified, supplier-stated, missing or not applicable |
| Likelihood | Score using the methodology below |
| Impact | Score using the methodology below |
| Inherent rating | Likelihood × impact |
| Treatment | Mitigate, avoid, transfer or accept |
| Owner | Role accountable for the action |
| Due date | Proposed target date |

### Task C — Apply a simple 5×5 risk method

**Likelihood**
- 1 — Rare: unlikely to occur.
- 2 — Unlikely: could occur, but not expected.
- 3 — Possible: might occur.
- 4 — Likely: expected to occur in some circumstances.
- 5 — Almost certain: expected to occur frequently or imminently.

**Impact**
- 1 — Insignificant: minimal disruption or harm.
- 2 — Minor: limited impact, readily recoverable.
- 3 — Moderate: meaningful operational, financial or privacy impact.
- 4 — Major: serious disruption, material loss or significant harm.
- 5 — Severe: critical business impact, extensive exposure or serious regulatory consequences.

Calculate the score as: **Risk score = Likelihood × Impact**.

Illustrative exercise bands:
- 1–4: Low
- 5–9: Moderate
- 10–16: High
- 17–25: Critical

These thresholds are for this learning exercise only. Organisations should define and approve their own risk criteria and risk appetite.

### Task D — Prepare an evidence request list

For each risk, specify what evidence you would request from the supplier. Consider:
- Data processing agreement and privacy terms.
- Data retention and deletion policy.
- Encryption and key-management documentation.
- Privileged-access and MFA configuration evidence.
- Current subprocessor register.
- Independent assurance report and scope.
- Incident notification and response commitments.
- Business continuity and disaster recovery information.

Do not mark a control as effective simply because a supplier says it exists. Record the evidence source, date, scope and limitations.

### Task E — Recommend treatment

For each High or Critical risk, recommend the control or contractual change required, the responsible owner, a target completion date, evidence needed to close the action, and whether residual risk requires formal acceptance.

## 5. Framework and regulatory context to research

Use these as reference points. Do not claim full compliance based on this exercise.

- **POPIA:** Consider the responsible party/operator relationship, security safeguards, processing purpose, retention and breach responsibilities.
- **ISO/IEC 27001:2022:** Consider supplier relationships, information security risk assessment and treatment, access control, information protection and incident management.
- **NIST Cybersecurity Framework 2.0:** Consider Govern, Identify, Protect, Detect, Respond and Recover.
- **NIST AI Risk Management Framework:** Consider governance, mapping, measurement and management of AI-related risks.

Record the exact clause, control or framework outcome you consult, and explain why it applies. Verify references against the official publications before using them in professional work.

## 6. Final deliverables

Save your completed work in this folder:
- `risk-register.csv` — at least five assessed risks.
- `supplier-evidence-request.md` — evidence requested and why.
- `assessment-summary.md` — scope, approach, key risks and recommendations.
- `reflection.md` — what you learned and what you would do differently.

## 7. Completion checklist

- [ ] I documented the chatbot data flow and key assumptions.
- [ ] I identified at least five third-party risks.
- [ ] I scored likelihood and impact consistently.
- [ ] I distinguished supplier statements from verified evidence.
- [ ] I prepared an evidence request list.
- [ ] I proposed risk treatment actions and owners.
- [ ] I documented residual risk and any acceptance decision required.
- [ ] I wrote a short management summary.

## 8. Reflection questions

1. Which risk would you escalate first, and why?
2. What is the difference between a supplier assertion and audit evidence?
3. What additional information would change your risk score?
4. Which risks could CapeConnect reduce through contract terms?
5. What would you tell management if the supplier cannot provide independent assurance?

---

**Important:** This is a fictional learning simulation. It is not a formal audit, legal opinion, POPIA compliance determination or ISO 27001 certification assessment.