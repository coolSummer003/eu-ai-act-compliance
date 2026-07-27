---
name: eu-ai-act-compliance
description: EU AI Act compliance workflow for risk classification, obligation mapping, transparency requirements, and documentation generation. Use when the user needs to assess whether their AI system falls under the EU AI Act, determine their risk tier, identify applicable obligations, generate compliance checklists, or prepare documentation before the August 2026 deadline.
---

# EU AI Act Compliance Quick Check

## Core Rule

Treat every AI system assessment as a compliance deliverable. First classify the system, then map obligations, then produce actionable output. Never guess risk tiers. Never promise full compliance.

## When Activated

Run this workflow when:

- The user wants to know if the EU AI Act applies to their AI system.
- The user needs to classify their AI system by risk tier.
- The user asks about Article 50 transparency obligations.
- The user needs a compliance checklist or gap analysis.
- The user mentions "EU AI Act", "AI regulation", "AI compliance", "August 2026", "high-risk AI", or "AI Act deadline".

## Key Dates

| Date | What Applies |
|------|-------------|
| 1 August 2024 | AI Act enters into force |
| 2 February 2025 | Prohibited practices banned; AI literacy duties apply |
| 2 August 2025 | GPAI model obligations apply |
| **2 August 2026** | **Article 50 transparency duties; high-risk obligations for Annex III** |
| 2 December 2027 | High-risk obligations (revised under Digital Omnibus) |
| 2 August 2028 | High-risk AI in regulated products (Annex I) |

## Intake

Before processing, determine:

1. What does the AI system do? Describe the use case in plain language.
2. Who is the provider? Who builds/brands the AI system?
3. Who is the deployer? Who uses the AI system in their workflow?
4. Is the AI system used in the EU or affecting EU residents?
5. What is the deployment context? (employment, education, credit, healthcare, law enforcement, critical infrastructure, etc.)

If the user has not described their AI system, ask for a brief use case description.

## Workflow

1. Classify the AI system by risk tier (prohibited, high-risk, limited, minimal).
2. Identify the user's role (provider, deployer, importer, distributor).
3. Map applicable obligations based on role and risk tier.
4. Check Article 50 transparency requirements.
5. Generate a compliance checklist with deadlines.
6. Produce a gap analysis if the user provides existing documentation.

## Risk Classification Guide

### Tier 1: Prohibited (Article 5)

These AI practices are banned outright:

- Social scoring by governments
- Real-time remote biometric identification in public spaces (with narrow exceptions)
- Manipulation of vulnerable groups
- Emotion recognition in workplaces and schools
- Untargeted scraping of facial images for facial recognition
- Predictive policing based solely on profiling
- AI that exploits vulnerabilities of age, disability, or social situation

**Action:** If the system falls here, advise the user to stop deployment immediately.

### Tier 2: High-Risk (Annex III + Annex I)

High-risk AI systems include:

- Biometric identification and categoration
- Critical infrastructure management
- Education and vocational training (grading, admission, assessment)
- Employment and worker management (recruitment, CV screening, task allocation)
- Access to essential services (credit scoring, insurance pricing, emergency services)
- Law enforcement
- Migration and border control
- Administration of justice and democratic processes

Also high-risk if embedded in regulated products (Annex I): medical devices, machinery, toys, aviation, cars, lifts, equipment, radio equipment, active implantable medical devices, civilian firearms, recreational craft, cableway appliances, pressure equipment, gondolas.

**Action:** Generate full obligation checklist for high-risk systems.

### Tier 3: Limited Risk (Article 50)

Systems that interact with humans or generate content:

- Chatbots and virtual assistants
- Emotion recognition systems
- Biometric categoration systems
- AI-generated text, images, audio, or video content (deepfakes)
- Text-to-speech and speech-to-text systems

**Action:** Article 50 transparency obligations apply from August 2026.

### Tier 4: Minimal Risk

Most AI systems fall here: spam filters, AI-enabled video games, inventory management, etc.

**Action:** No specific obligations beyond AI literacy (Article 4).

## Obligation Mapping

### For Providers (Article 16)

High-risk AI providers must:

1. Risk management system (Article 9)
2. Data governance (Article 10)
3. Technical documentation (Article 11)
4. Record-keeping / logging (Article 12)
5. Transparency and information to deployers (Article 13)
6. Human oversight measures (Article 14)
7. Accuracy, robustness, and cybersecurity (Article 15)
8. Quality management system (Article 17)
9. Conformity assessment (Article 43)
10. EU database registration (Article 49)
11. Post-market monitoring (Article 72)

### For Deployers (Article 26)

High-risk AI deployers must:

1. Use the system in accordance with instructions
2. Assign human oversight
3. Ensure input data is relevant
4. Monitor system operation
5. Inform affected persons
6. Keep logs automatically generated
7. Conduct data protection impact assessment if needed
8. Inform authorities of serious incidents
9. Conduct fundamental rights impact assessment for public bodies
10. Ensure staff training
11. Report non-compliance to authorities

### Article 50 Transparency Obligations (August 2026)

From August 2026, ALL systems must:

- Inform users when interacting with an AI system (chatbots, virtual assistants)
- Label AI-generated content as artificially generated
- Label deepfakes and AI-generated text on matters of public interest
- Embed machine-readable markers in AI-generated content
- Inform people when subject to emotion recognition or biometric categoration

## Output Standard

```markdown
## System Classification

- System name:
- Use case:
- Risk tier: [Prohibited / High-Risk / Limited / Minimal]
- Basis for classification:

## Role Assessment

- Provider / Deployer / Importer / Distributor:
- Jurisdiction:

## Applicable Obligations

[Ranked by priority and deadline]

## Article 50 Transparency Check

[Specific to August 2026 deadline]

## Compliance Checklist

[ ] Item 1
[ ] Item 2
...

## Gap Analysis (if applicable)

## Next Steps
```

## Template Routing

Read `references/risk-classifier.md` when classifying a specific AI system.

Read `references/article-50-checklist.md` when checking transparency obligations.

Read `references/deployer-obligations.md` when the user is a deployer, not a provider.

Read `references/fine-calculator.md` when the user asks about penalties.

## Quality Bar

Always separate:

- Classification: factual risk tier based on the use case description
- Obligation: what the regulation requires for that tier
- Action: what the user can do this week
- Uncertainty: where legal advice is recommended

For high-risk systems, never hide the scope of obligations. For limited-risk systems, emphasize the August 2026 deadline. For prohibited systems, recommend immediate cessation.

Do not promise compliance. The EU AI Act requires ongoing processes, not a one-time checklist.
