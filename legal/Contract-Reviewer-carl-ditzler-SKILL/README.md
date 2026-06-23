# Contract Reviewer Skill

A comprehensive contract review skill that helps identify legal, business, operational, compliance, privacy, security, technology, and AI-related risks in contracts and other legal documents.

The goal is not to replace attorney review. The goal is to help reviewers quickly understand what matters, what is unusual, what is missing, and where additional review or negotiation may be needed.

## What This Skill Is

This skill is an AI-assisted contract review and risk analysis tool.

It is designed to analyze contracts, identify issues, surface risks, explain why they matter, and provide recommendations for consideration.

The skill can be used by legal, procurement, compliance, privacy, security, and business teams to accelerate contract review and improve issue spotting.

## What This Skill Is Not

This skill is not a Contract Lifecycle Management (CLM) system. CLM platforms are designed to manage the lifecycle of contracts through workflows, approvals, repositories, obligation management, reporting, renewals, and integrations.

This skill focuses on contract analysis rather than contract management, and is intended to complement CLM platforms such as Ironclad, Agiloft, DocuSign CLM, Sirion, ContractPodAI, Icertis, Conga, and similar solutions.

While CLMs manage the contract lifecycle, this skill focuses on:

- Contract review
- Contract analysis
- Risk assessment
- Issue spotting
- Negotiation support
- Legal document review
- Contract intelligence
- AI-assisted contract review

## What It Reviews

This skill reviews contracts from legal, business, compliance, privacy, security, technology, and AI angles, rather than limiting review to only contract clauses, such as:

- Commercial terms
- Legal risks
- Operational obligations
- Compliance requirements
- Privacy and data protections
- Information security requirements
- IP terms
- Vendor and third-party risks
- AI-related provisions
- Governance and reporting obligations
- Missing protections or unclear language

It also identifies potential issues, explains why they matter, and provides recommendations.

## Intended Users

This skill may be useful for:

- Legal departments
- Legal Operations teams
- Procurement teams
- Contract managers
- Compliance professionals
- Privacy teams
- Security teams
- Business stakeholders involved in contract review

## Output

Depending on the document and instructions provided, the skill may generate:

- Executive summaries
- Key terms and obligations
- Risk assessments
- Negotiation considerations
- Missing clause analysis
- Detailed findings and recommendations
- Questions for internal stakeholders
- Escalation items requiring attorney review

## Considerations

Outputs should always be reviewed by appropriate legal, compliance, privacy, security, procurement, or business stakeholders.

The skill can identify issues and provide analysis, but it cannot determine business risk tolerance, negotiation strategy, or legal conclusions for a specific jurisdiction.

It's essential that a legal professional reviews contracts.

## Token Use

This skill is thorough and, as a result, it can consume a ***significant number of tokens*** with Claude or OpenAI, particularly when reviewing:

- Long agreements
- Multiple documents
- Exhibits and schedules
- Attachments incorporated by reference
- Large vendor contracts
- Complex commercial transactions

Detailed reviews and reports can substantially increase token usage, processing time, and model costs.

## Best Results

For the most complete review:

- Provide the full agreement when possible.
- Include exhibits, schedules, attachments, and referenced documents.
- Provide relevant business context.
- Identify any specific concerns or focus areas.
- Validate findings before relying on them for legal or business decisions.

## Note on CLM Capabilities

One objective during development was to explore whether a skill or agent could provide functionality typically found in Contract Lifecycle Management (CLM) systems. While the LLM performed well for contract review, issue spotting, risk analysis, identification, and recommendations, I found that Skill implementations are not ready for many core CLM capabilities, including:

* Contract repositories
* Structured contract records
* Workflow orchestration
* Approval routing
* Obligation management
* Renewal management
* Reporting and dashboards
* System integrations, especially Salesforce
* **Persistent contract metadata**

As a result, this project focuses on contract review and analysis rather than contract lifecycle management. That said, portions of the skill may serve as a foundation for future CLM experimentation. The current features could be extended into broader contract intelligence or CLM workflows as underlying AI platforms like Claude and OpenAI mature.

For now, I view this project as a contract review and contract intelligence capability, rather than a  CLM platform replacement.

## Disclaimer

This skill provides analysis and recommendations for informational purposes only. It does not provide legal advice and should not be relied upon as a substitute for advice from qualified legal counsel.
