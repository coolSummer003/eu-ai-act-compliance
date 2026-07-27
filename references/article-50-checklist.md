# Article 50 Transparency Checklist

**Deadline: 2 August 2026**

Article 50 applies to ALL AI systems regardless of risk tier. This checklist covers the transparency obligations that take effect on 2 August 2026.

## 1. Chatbot and Virtual Assistant Disclosure

**Requirement:** Users must be informed when they are interacting with an AI system.

- [ ] Add clear disclosure in UI that the system is AI-powered
- [ ] Disclosure must be visible before or at first interaction
- [ ] Cannot be hidden in terms of service or legal text
- [ ] Applies to: customer support bots, virtual assistants, AI-powered search, AI copilots

**Implementation examples:**
- Banner text: "You are chatting with an AI assistant"
- Label on input field: "AI-generated response"
- First-message disclosure in chat flow

## 2. AI-Generated Content Labeling

**Requirement:** AI-generated or AI-manipulated content must be machine-readable labeled.

- [ ] Embed metadata in AI-generated images (C2PA standard recommended)
- [ ] Embed metadata in AI-generated audio
- [ ] Embed metadata in AI-generated video
- [ ] Embed metadata in AI-generated text (where technically feasible)
- [ ] Labels must survive content sharing and redistribution

**Technical requirements:**
- Machine-readable marking (not just visible label)
- Must be present at time of publication
- Applies to content that informs matters of public interest

## 3. Deepfake Disclosure

**Requirement:** Deepfakes and AI-generated text published to inform on matters of public interest must be clearly labeled.

- [ ] Label AI-generated text in news or public interest content
- [ ] Label synthetic faces, voices, or bodies in media
- [ ] Label must be clear and unambiguous
- [ ] Applies to: media companies, political campaigns, social media publishers

## 4. Emotion Recognition Disclosure

**Requirement:** Deployers must inform people when they are subject to emotion recognition or biometric categoration.

- [ ] Inform subjects before emotion recognition is used
- [ ] Inform subjects before biometric categoration is used
- [ ] Disclosure must be clear and timely
- [ ] Applies to: HR tools, customer service analytics, retail analytics

## 5. AI-Generated Text Disclosure (Public Interest)

**Requirement:** AI-generated text published on matters of public interest must be labeled.

- [ ] Label AI-written articles, reports, or summaries
- [ ] Label AI-generated legal documents or filings
- [ ] Label AI-generated scientific content
- [ ] Applies to: publishers, content platforms, news organizations

## 6. Watermarking and Technical Markers

**Requirement:** Providers of general-purpose AI models must ensure outputs are marked.

- [ ] Implement machine-readable watermarking
- [ ] Use technical standards (C2PA, IPTC, or equivalent)
- [ ] Markers must be robust against removal
- [ ] Applies to: ChatGPT, Claude, Gemini, and similar models

## Quick Compliance Actions

### If you deploy a chatbot or virtual assistant:
1. Add "AI assistant" label to chat interface
2. Add first-message disclosure
3. Document the disclosure in your AI system inventory

### If you generate AI content for publication:
1. Enable metadata embedding in your AI tools
2. Add visible labels to AI-generated content
3. Document your labeling process

### If you use emotion recognition or biometric categoration:
1. Notify affected individuals
2. Update privacy notices
3. Document the notification process

### If you publish AI-generated text on public interest topics:
1. Label the content as AI-generated
2. Disclose AI involvement in editing or drafting
3. Document the labeling practice

## What Is NOT Required (Common Misconceptions)

- You do NOT need to register in the EU AI database for limited-risk systems
- You do NOT need a conformity assessment for limited-risk systems
- You do NOT need to conduct a fundamental rights impact assessment for limited-risk systems
- You do NOT need to implement human oversight for limited-risk systems

## Documentation Template

```
System: [Name]
Risk tier: Limited
Transparency obligations: [List applicable obligations]
Implementation status: [Complete / In progress / Not started]
Deadline: 2 August 2026
Responsible person: [Name]
Evidence: [Where disclosure/labeling is implemented]
```
