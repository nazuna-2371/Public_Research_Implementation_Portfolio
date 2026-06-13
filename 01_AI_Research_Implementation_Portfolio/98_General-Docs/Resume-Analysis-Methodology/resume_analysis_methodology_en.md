
---

# Analysis Procedure and Evaluation Design for Capabilities and Skills in Resume Preparation

---

## 1. Purpose

This document is a supplementary document explaining what information was used, from what perspectives it was organized and analyzed, and what scope was treated as publicly shareable information for the diagrams and body text included in the resume.

In the main resume, in order to allow readers to understand the overview in a short amount of time, practical work experience, publicly shareable research outputs, currently non-public personal R&D, and the contents of each system are compressed into capability categories that can be explained in a professional context.

The purpose of this document is to clarify the following points.

```text
・What information the diagrammed resume and body text were based on
・What evaluation perspectives were used to organize areas of strength and work-related strengths
・How publicly shareable outputs were separated from currently non-public personal R&D and each system
・To what extent LLMs were used as an auxiliary tool
・That responsibility for confirming the content lies with the creator
```

This document is not intended to exaggerate years of experience or the volume of work history.  
Its purpose is to organize, in a form that can be explained in a resume, the thinking tendencies, design capabilities, evaluation perspectives, and process of turning ideas into outputs that can be confirmed from the creator's practical work experience and personal R&D.

---

## 2. Target Data

The information analyzed mainly includes the following.

```text
・Practical work experience
・Input text and dialogue content provided by the creator (materials for identifying thinking tendencies)
・Publicly shareable research outputs
・Currently non-public personal R&D and each system
・Previously created design documents, specification drafts, evaluation axes, and diagrammed materials
・Considerations related to AI utilization, LLM evaluation, AI governance, evidence/trace design, and development support
```

### 2.1 Practical Work Experience

Practical work experience was organized from the following perspectives.

```text
・Data management
・Business process improvement
・Web scraping and automation using Python
・AI chatbot-related work
・Data science
・Observation, improvement, evaluation, and recognition of operational issues related to AI utilization
```

Here, the analysis does not simply list work history.  
Instead, it treats as objects of confirmation the problem identification, business organization, detection of discomfort or inconsistencies in AI utilization, and the possibility of connecting these observations to specification and improvement.

### 2.2 Publicly Shareable Research Outputs

MARGPA and its related materials are included as representative publicly shareable outputs.

```text
MARGPA: Modular AI Runtime Governance Prompting Architecture
https://github.com/nazuna-2371/margpa/
```

For MARGPA-related materials, perspectives such as LLM reasoning, context preservation, premise fixation, contradiction handling, self-repair, and runtime governance were organized into capability categories that can be explained in a resume.

### 2.3 Currently Non-Public Personal R&D and Each System

For currently non-public personal R&D and each system, research names, detailed structures, internal specifications, and concrete connection relationships are not directly described in the resume body.

However, the following capabilities that can be confirmed through them are abstracted as capability categories that can be explained in a resume.

```text
・AI governance design
・AI evaluation design
・Tamper resistance and audit trail design
・Auditability design
・Safety and risk management design
・Dialogue context continuity design
・Analysis of failure patterns in AI utilization
・Development support, specification design, and documentation
・Structuring of multimodal information and expressive data
```

The phrase "currently non-public" here does not mean permanently non-public.  
After confirming maturity, publication scope, safety, reusability, and misuse risks, items that can be made public are intended to be open-sourced at an appropriate timing.

---

## 3. Evaluation Perspectives

The resume diagrams were organized mainly from the following perspectives.

```text
・AI Governance
・Auditability
・AI Accountability
・AI Transparency
・AI Risk Management
・LLM Evaluation Design
・Runtime Governance
・Traceability / Evidence Design
・AI Safety Governance
・Specification Design
・Documentation / Docs Design
・AI-assisted Development Support
```

### 3.1 AI Governance

This is the perspective of treating AI not merely as an output device, but as a governance target that includes objectives, constraints, scope of responsibility, behavior in failure cases, repair procedures, and auditability.

The confirmed capability categories are as follows.

```text
・Ability to organize the design intent of AI systems
・Ability to define AI outputs and behavior as evaluation targets
・Ability to separate objectives, constraints, exceptions, repair, and operation
・Ability to clarify responsibility boundaries in AI utilization
```

### 3.2 Auditability / Traceability

This is the perspective of handling AI outputs, judgments, corrections, failures, and context continuity in a form that can be checked later.

The confirmed capability categories are as follows.

```text
・Design that preserves the basis for judgments
・Design that tracks the premises and context of outputs
・A stance that emphasizes a state in which later verification, audit, and repair are possible
・Ability to convert subjective or individual judgment into structures, records, and procedures
```

### 3.3 AI Accountability

This is the perspective of organizing who is responsible for what in AI systems and AI utilization, what can be delegated to AI, and where human confirmation is required.

The confirmed capability categories are as follows.

```text
・Separation of responsibility scope
・Design of human confirmation points
・Operational design that does not trust AI outputs as-is
・Design of repair paths for erroneous outputs and failures
```

### 3.4 AI Transparency

This is the perspective of making the grounds, premises, constraints, judgment process, and limitations of AI outputs easy for users and stakeholders to inspect.

The confirmed capability categories are as follows.

```text
・Explicit statement of premises and judgment criteria
・Explicit statement of uncertainty and limitations
・Conversion into explainable materials, diagrams, and specifications
・Information compression according to the reader
```

### 3.5 AI Risk Management

This is the perspective of detecting and organizing erroneous outputs, premise deviation, overgeneralization, overtrust induction, insufficient grounds, and side effects of safety behavior in AI utilization.

The confirmed capability categories are as follows.

```text
・Prior detection of failure paths
・Classification of risk factors
・Detection of excessive suppression and overgeneralization
・Design of repair, degradation, and re-evaluation in failure cases
```

### 3.6 LLM Evaluation Design

This is the perspective of evaluating LLM output quality not only by correctness, but also by premise preservation, contradictions, grounds, context continuity, overgeneralization, answer structure, and repairability.

The confirmed capability categories are as follows.

```text
・Detection of contradictions in LLM outputs
・Detection of premise deviation
・Evaluation of context preservation
・Detection of insufficient grounds
・Detection of generalization and averaging
・Design of evaluation axes
```

---

## 4. Analysis Procedure

The analysis was conducted through the following flow.

```text
1. Input of thinking, experience, outputs, and each system
2. Decomposition of information
3. Organization into capability categories
4. Separation of publicly shareable scope and currently non-public scope
5. Compression for resume use
6. Diagramming
7. Confirmation and revision by the creator
```

### 4.1 Input of Thinking, Experience, Outputs, and Each System

First, practical work experience, personal R&D, publicly shareable research outputs, currently non-public systems, design notes, specification drafts, evaluation axes, and past dialogue content were organized as input information.

At this stage, the purpose was not to decide whether each item should be placed directly in the resume, but to broadly confirm what kinds of problems the creator had handled, from what perspectives they had designed, and what kinds of outputs they had produced.

### 4.2 Decomposition of Information

The input information was decomposed into the following types of units.

```text
・Problems being handled
・Design targets
・Evaluation targets
・Failure patterns
・Repair methods
・Responsibility boundaries
・Methods of evidence/trace creation
・Public shareability
・Applicability to work
```

This made it possible to organize the information not merely as output names or research names, but as capability elements that can be explained in a professional context.

### 4.3 Organization into Capability Categories

The decomposed information was organized into capability categories that can be communicated clearly in a resume.

Examples of such conversion are as follows.

```text
Observation of premise drift and contradictions in LLMs
→ LLM evaluation design, AI observation capability, contradiction detection capability

Design that allows dialogue history and judgment grounds to be checked later
→ Auditability, Traceability, evidence/trace design

Focus on overgeneralization by AI and side effects of safety behavior
→ AI Risk Management, AI Safety Governance

Work that converts complex concepts into specifications, documents, and diagrams
→ Specification design, documentation design, upper-level design with technical understanding
```

### 4.4 Separation of Publicly Shareable Scope and Currently Non-Public Scope

Information to be included in the resume was separated according to the following criteria.

```text
Publicly shareable:
・MARGPA and related public materials
・Capability categories that can be explained within a publicly shareable scope
・Areas of strength applicable to work
・Abstracted tendencies of outputs from personal R&D

Currently non-public:
・Proper names of personal R&D and each system other than MARGPA
・Detailed internal structures
・Implementation procedures
・Internal connection relationships
・Pre-publication specification details
・Information that may invite misuse or excessive reproduction
```

Through this separation, the resume is structured to explain capabilities and design tendencies while avoiding excessive disclosure of research content that is not yet ready for publication.

### 4.5 Compression for Resume Use

Because presenting the full analysis results as long-form text would increase the burden on the reader, the resume compresses the information according to the following principles.

```text
・Prioritize areas of strength that should be communicated in a professional context
・Express content using capability categories rather than research names
・Show applicability to work rather than detailed specifications
・Use diagrams to improve visibility of abstract concepts
・Use expressions that can be connected to grounds, rather than excessive self-evaluation
```

### 4.6 Diagramming

The first and second pages of the resume were diagrammed so that readers can understand the content in a short amount of time.

```text
Page 1:
Summarizes areas of strength centered on AI Governance / Auditability / LLM Evaluation Design,
currently publicly shareable representative outputs, and work-related strengths.

Page 2:
Organizes capability structure, applicability to work, design strengths,
and abstracted personal R&D that serves as supporting grounds.
```

Diagramming is used not only to reduce the amount of text, but also to show how the creator's areas of strength connect to one another.

### 4.7 Confirmation and Revision by the Creator

LLMs are used as an auxiliary tool for structure, wording, and diagramming, but the creator is responsible for the appropriateness of the content, publication scope, expression, and final responsibility.

LLM outputs are not adopted as-is.  
The following points are checked.

```text
・Whether any content differs from the facts
・Whether years of experience or practical work experience are exaggerated
・Whether currently non-public research names or detailed structures are exposed
・Whether the expressions are unlikely to cause misunderstanding as a resume
・Whether the content is at a granularity that can be explained as capability categories
```

---

## 5. Scope of LLM Usage

LLMs are used as an auxiliary tool in the preparation of this resume and related diagrammed materials.

The main scope of usage is as follows.

```text
・Organizing information
・Drafting document structures
・Adjusting wording
・Classifying information into capability categories
・Organizing diagramming policies
・Compressing long-form information
・Assisting in separating publicly shareable scope from currently non-public scope
・Preparing Japanese and English expressions
```

On the other hand, the following are not delegated to LLMs.

```text
・Fact-checking of career history and outputs
・Final judgment on public disclosure
・Judgment of ownership over research content
・Final responsibility for the written content
・Decision on whether to submit the resume
```

LLMs are used as auxiliary tools for organizing the creator's thinking, experience, and outputs.  
Final confirmation of the written content and responsibility for it remain with the creator.

---

## 6. Compression Policy

The resume does not attempt to cover all research content or design details.  
Instead, it prioritizes the following so that readers can understand the content in a short amount of time.

```text
・What the main axis is
・What kinds of problems have been handled
・Which capability categories they connect to
・What representative publicly shareable outputs exist
・In what kinds of work roles value can be created
```

On the other hand, the following are not detailed in the resume.

```text
・Full specifications of each system
・Proper names of currently non-public personal R&D and each system
・Internal document structures
・Implementation procedures
・Detailed connection relationships
・Information that may invite misuse or excessive reproduction
```

Through this compression, the main resume is structured so that the creator's areas of strength and work-related strengths can be understood in a short amount of time.

---

## 7. Notes on Interpretation

The diagrammed materials in this resume do not represent practical work experience alone.  
They are the result of analysis that includes practical work experience, personal R&D, publicly shareable research outputs, and currently non-public system designs.

Therefore, the diagrammed capability categories mean the following.

```text
・Areas handled through practical work experience
・Areas continuously designed and examined through personal R&D
・Areas that can be confirmed from publicly shareable research outputs
・Design capabilities applicable to work
```

On the other hand, they do not mean the following.

```text
・A claim that everything was performed as practical work experience
・A claim that there are many years of practical experience in every area
・A claim that details of currently non-public personal R&D and each system have been disclosed
・A claim that LLM outputs were adopted as career history as-is
```

This document presents the analysis procedure for organizing the creator's experience, research, and outputs into a form that can be explained in a resume.

---

## 8. Summary

This resume organizes the creator's practical work experience and personal R&D as areas of strength centered on AI Governance / Auditability / LLM Evaluation Design.

For publicly shareable outputs such as MARGPA, links are provided.  
For currently non-public personal R&D and each system, research names and detailed structures are not disclosed, and the content is abstracted into capability categories.

LLMs are used for structure organization, wording adjustment, and diagramming support, but confirmation of the written content and final responsibility remain with the creator.

This document explains that the diagrammed content included in the resume is not a mere self-evaluation, but an organized and analyzed result based on thinking, experience, and outputs.

---
