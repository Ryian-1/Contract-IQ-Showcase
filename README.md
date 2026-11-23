# Contract IQ

**A Structured Contract Review & Negotiation Workspace for macOS**

Contract IQ is a macOS LegalTech application designed to bring greater structure, consistency, and review discipline to contract analysis and negotiation preparation. Built with SwiftUI, AppKit, and Firebase, the application brings AI-assisted clause drafting together with negotiation playbooks, clause comparison, revision history, and exportable review documentation in a focused desktop workflow.

The product is designed around a practical principle: AI can accelerate the preparation and refinement of contractual language, while substantive review, negotiation decisions, and approval remain under human control. Contract IQ supports the work surrounding a contract; it is not a substitute for legal judgment or professional advice.

## Product Overview

Contract review often involves more than reading a document and suggesting alternative wording. Reviewers need to assess proposed language against an existing position, prepare negotiation responses, consider fallback wording, track successive revisions, and communicate the outcome in a form that can be reviewed later.

Contract IQ brings these activities into a structured workflow. It provides a dedicated environment for drafting and refining clauses, maintaining negotiation positions, examining differences between original and proposed language, and assembling review material into a consistent output.

The application is positioned as a contract-workflow productivity tool for users involved in legal operations, contract administration, commercial review, and negotiation preparation.

## Core Capabilities

### AI-Assisted Clause Drafting and Revision

Supports the preparation, refinement, and revision of contractual clauses with AI-assisted language workflows. The objective is to make clause development more structured and iterative, while keeping the proposed wording visible for human assessment and approval.

### Negotiation Playbooks and Fallback Positions

Provides support for organising negotiation approaches, preferred positions, and fallback language. This helps make negotiation preparation more deliberate by giving reviewers a structured place to consider alternative positions rather than treating every clause revision as an isolated drafting exercise.

### Original-versus-Proposed Clause Comparison

Enables reviewers to examine original contractual wording alongside proposed language. Side-by-side evaluation helps bring the nature of a proposed change into focus and supports more informed review of revisions before they are accepted or carried forward.

### Revision History and Human Review

Maintains a revision-oriented workflow so that changes can be considered in context and review activity can remain organised across iterations. Contract IQ is designed to support human oversight: AI-assisted suggestions are inputs to a review process, not autonomous contractual decisions.

### Structured Review-Package Export

Provides Markdown-based export of structured review material. This creates a portable representation of the review output that can be retained, shared, or used as supporting documentation in subsequent review and negotiation activities.

## Workflow Approach

Contract IQ brings together several connected stages of contract review and negotiation preparation:

1. **Draft and refine** — prepare proposed clause language through an AI-assisted drafting workflow.
2. **Establish negotiation positions** — organise preferred positions and fallback alternatives using negotiation playbooks.
3. **Evaluate proposed changes** — compare original wording with proposed language as part of the review process.
4. **Retain revision context** — maintain continuity across revisions and human review.
5. **Prepare review documentation** — export structured review material in Markdown format.

These capabilities are intended to support a more consistent review process and clearer handling of proposed contractual changes.

## Product and Engineering

Contract IQ is developed as a native macOS application, with a technology foundation centred on:

| Layer | Technology |
| --- | --- |
| Application language | Swift |
| User interface | SwiftUI |
| macOS integration | AppKit |
| Authentication | Firebase Authentication |
| Data platform | Cloud Firestore |
| Review documentation | Markdown export |

The native macOS approach provides a dedicated desktop experience for focused review workflows. Firebase Authentication and Cloud Firestore form part of the application's backend foundation.

## Design Principles

- **Human-led decision-making:** contractual interpretation, approval, and negotiation decisions remain subject to human review.
- **Structured workflows:** drafting, negotiation positions, comparison, revisions, and review outputs are treated as connected activities.
- **Review transparency:** proposed language and revision context are kept central to the review process.
- **Practical documentation:** structured Markdown exports support retention and downstream review of generated material.
- **Purpose-built desktop experience:** the application is designed around macOS rather than presented as a generic web interface.

## Scope and Professional Use

Contract IQ is intended to assist with contract-review preparation and the organisation of negotiation workflows. It does not independently determine legal enforceability, provide authoritative legal opinions, approve agreements, or replace review by a qualified legal professional. AI-generated or AI-assisted contractual language must be evaluated in its specific legal, commercial, and factual context before being used in an agreement.

## Project Showcase

This repository presents the public-facing showcase for Contract IQ. It documents the product's purpose, capabilities, and technical direction without serving as the private application source repository.

---

**Contract IQ — bringing structure, review discipline, and human oversight to AI-assisted contract workflows.**
