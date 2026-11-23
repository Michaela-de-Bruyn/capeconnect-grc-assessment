
# AI Chatbot Data Flow

## 1. Purpose

This document describes the proposed movement of customer information through CapeConnect's AI-powered customer support chatbot.

The data flow is hypothetical and will be validated against evidence during the assessment.

## 2. Proposed Data Flow

```text
CUSTOMER
   |
   | Submits support enquiry
   v
CHATBOT INTERFACE
   |
   | Captures customer information
   v
CAPEConnect APPLICATION
   |
   | Sends enquiry to external AI provider
   v
THIRD-PARTY AI PROVIDER
   |
   | Processes enquiry and generates response
   v
CHATBOT INTERFACE
   |
   | Displays response
   v
CUSTOMER

Additional flow:
Chatbot conversation history
   |
   v
Storage location (UNKNOWN)
   |
   v
Authorised CapeConnect support employees
```

## 3. Information Flow

| Stage | Activity | Information | Key Risk |
|---|---|---|---|
| 1 | Customer submits enquiry | Name, email, enquiry | Excessive data collection |
| 2 | Chatbot captures enquiry | Customer information | Unauthorised access |
| 3 | Application sends enquiry to provider | Conversation content | Third-party exposure |
| 4 | AI provider processes enquiry | Customer information | Unauthorised model training |
| 5 | Response returns to chatbot | Generated response | Inaccurate or inappropriate output |
| 6 | Conversation history is stored | Support history | Retention and storage risks |
| 7 | Employee accesses conversation | Customer information | Excessive permissions |

## 4. Trust Boundaries

The assessment identifies three important trust boundaries:

1. Customer to CapeConnect: Information enters the company's environment.
2. CapeConnect to AI provider: Information may leave the company's direct control.
3. Stored conversation history to employees: Internal users access customer information.

## 5. Unknown Technical Details

The following require evidence:

- Whether data is encrypted in transit and at rest.
- Where the provider hosts and stores information.
- Whether conversations are retained by the provider.
- Whether conversations are used to train AI models.
- Whether customer information is anonymised or minimised.
- Which employees can access conversation histories.
- Whether access is logged and monitored.
- Whether deletion requests propagate to the provider.

## 6. GRC Assessment Considerations

The data flow creates assessment requirements relating to:

- POPIA lawful processing and security safeguards.
- Third-party service provider oversight.
- Access control and least privilege.
- Data retention and deletion.
- Information security monitoring.
- AI governance and transparency.

## 7. Assessment Status

Status: Initial proposed data flow.

This diagram represents the current assessment hypothesis, not a verified technical architecture. Evidence and stakeholder interviews must confirm the actual flow.
