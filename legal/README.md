# Legal AI Agents and Skills

## AI Agents and Skills for Legal, Compliance, and Risk

This folder includes AI agents and skills designed for legal, compliance, privacy, and risk use cases.

These agents and skills include structured instructions for LLMs, including Claude, Codex, and similar models, to enable more consistent execution of complex legal workflows such as contract review, AI governance, outside counsel management, and regulatory analysis.

This folder is intended for attorneys, law firms, in-house legal teams, legal operations and legal technology teams, and compliance, privacy, and risk professionals to experiment. It is provided for demonstration purposes and is designed to show how AI can be applied in legal and similar environments with structure and operational fit, rather than through ad hoc prompting, and how AI can be tailored to specific use cases.

## What These Agents and Skills Do

Each agent and skill is designed to approach a problem in a structured way and provide value. This may include structured intake and issue framing; identification of missing facts and required documents; risk spotting across legal domains such as contracts, privacy, and regulatory matters; application of playbooks, policies, and guidelines; and generation of outputs such as reports, redlines, scorecards, and recommendations. Where appropriate, the agent or skill may also identify escalation points and clarify human review needs.

These agents and skills are intended to support complex, high-volume operational work and higher-risk analytical work, including billing review, intake triage, contract review, AI governance assessments, issue identification, and related legal team workflows.

## Design Principles

These legal AI agents and skills are designed with structure, risk awareness, human review boundaries, and repeatability.

They are more than prompts. They define a role and perspective, a step-by-step workflow, required inputs, fallback handling, guardrails, constraints, and output formats designed for real legal and operational use.

They are built with explicit awareness of legal and governance risk. Depending on the use case, this may include attorney-client privilege, confidentiality, privacy and data handling, regulatory and jurisdictional considerations, unauthorized practice of law risks, cross-border considerations, and model limitations such as hallucination risk.

They also establish boundaries between what AI may autonomously do and what should be reviewed by an attorney or other qualified professional. Outputs should be treated as a demonstration of draft work product.

Where appropriate, these agents and skills are designed for auditability and repeatability. Outputs are structured so they can be reviewed, validated, compared across matters or vendors (especially against legal AI vendors), and incorporated into reporting or governance processes.

## Example Agent and Skill Categories

This folder may include agents and skills covering areas such as contract review and redlining, AI governance review, outside counsel billing and performance review, legal intake and triage automation, regulatory or compliance analysis, and vendor or AI tool assessment. Additional practice areas and use cases are planned.

## Intended Use

These agents and skills are intended for demonstration purposes only, including demonstration in LLM environments such as Claude or Codex, demonstration as embedded components within internal tools or workflows, and demonstration as adapted implementations aligned to organization-specific playbooks, policies, and data environments.

They are not production systems. They are reference implementations intended to demonstrate how to design reliable and structured legal AI workflows.

## Limitations and Assumptions

These agents and skills rely on user-provided inputs and do not independently verify facts. Legal accuracy depends on jurisdiction, context, completeness of information, and the quality of any referenced materials. Outputs may be incomplete, wrong/inaccurate, or outdated and should be reviewed.

These agents and skills do not replace qualified legal counsel or other professionals, and do not constitute legal or other professional advice. All analysis is for demonstration purposes only and constitutes draft work product. It must not be relied upon without appropriate review, including where a use case involves higher-risk analysis such as contract interpretation or regulatory guidance; review by a qualified legal professional is required.

## Security and Data Handling Considerations

Before using these agents and skills in any environment, confirm that the AI system and the data involved are appropriate for one another.

Confidential, privileged, regulated, or otherwise sensitive information should not be entered into unsecured or public AI systems. Users are responsible for determining what information may be shared with AI.

Use of these agents and skills should be evaluated in light of internal data handling policies, professional responsibility obligations, client or counterparty confidentiality commitments, and applicable privacy and security laws. It is also important to confirm whether the AI provider stores prompts or outputs, uses submitted content for training, or otherwise handles data in ways that may be inconsistent with organizational requirements.

## Author and License

Carl Ditzler
AI | Legal Technology | Legal Operations

I am open to work following a recent workforce reduction. If you’d like to discuss an opportunity or learn more about my experience, please see my LinkedIn profile:

https://www.linkedin.com/in/carlditzler/

Use, modification, and distribution must comply with the Apache License 2.0.

## Disclaimer

THESE AGENTS AND SKILLS ARE PROVIDED "AS IS" WITHOUT WARRANTIES OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ACCURACY, COMPLETENESS, OR FITNESS FOR A PARTICULAR PURPOSE.

I DISCLAIM ALL LIABILITY FOR ANY LOSS, DAMAGE, OR CLAIM ARISING FROM THEIR USE OR MISUSE.

These materials are not legal advice, do not create an attorney-client relationship, and are not a substitute for qualified legal or other professional advice.

Users are solely responsible for how they use these agents and skills, including any reliance on outputs. All outputs should be independently reviewed and validated.

## OpenAI Notes

These files work well with Codex Skills and, to an extent, structured system prompts. They would generally be stronger when paired with tool access such as files, APIs, or internal knowledge sources. For workflow automation use cases, structured output schemas such as JSON can improve reliability.

## Anthropic Claude Notes

These files are designed to work well with Claude Skills. They perform best when supporting materials are separated into components such as instructions, playbooks, intake forms, output formats, and test plans. Performance improves further when the skill includes explicit failure modes, escalation rules, and review boundaries.
