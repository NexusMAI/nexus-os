# Nexus OS Engineering Constitution

**Status:** Ratified · Supreme Governing Document  
**Authority:** This Constitution supersedes all other Nexus OS guidance except explicit amendments recorded in Section 28.  
**Applies to:** All human engineers, AI agents, workflows, projects, skills, prompts, and subsystems operating on Nexus OS.

---

## 1. Preamble & Purpose

This Constitution establishes the permanent engineering laws of Nexus OS, an AI-First Engineering Operating System.

Nexus OS exists to standardize how production-grade AI software is researched, designed, built, evaluated, deployed, and improved through structured workflows, reusable knowledge, and accountable human–AI collaboration.

All participants MUST treat this document as binding law. Compliance is mandatory, not advisory.

---

## 2. Core Engineering Values

The following values govern all decisions when rules do not explicitly resolve a conflict.

1. **Correctness over speed.** Work MUST NOT advance at the expense of verified quality.
2. **Clarity over cleverness.** Designs, artifacts, and decisions MUST be understandable by future engineers and agents.
3. **Reuse over reinvention.** Proven patterns MUST be preferred over novel solutions unless a documented exception is approved.
4. **Accountability over autonomy.** Every action MUST have a traceable owner.
5. **Evidence over assumption.** Claims of readiness MUST be supported by evaluation results, not opinion.
6. **Safety over convenience.** Safety and reliability constraints MUST NOT be bypassed for delivery pressure.

---

## 3. Scope & Separation of Concerns

**Rule 3.1 — Platform Scope.** Nexus OS MUST govern methodology, workflows, knowledge, capabilities, evaluation, policy, and platform standards.

**Rule 3.2 — Domain Exclusion.** Domain-specific business logic MUST reside in application projects, not in Nexus OS platform assets.

**Rule 3.3 — Boundary Preservation.** Platform subsystems MUST NOT embed product-specific domain rules.

**Rule 3.4 — Inheritance.** All projects built on Nexus OS MUST inherit platform lifecycle, evaluation, policy, and orchestration standards.

**Rule 3.5 — No Scope Creep.** Projects MUST NOT expand platform scope without an approved amendment to this Constitution or a ratified architecture change.

---

## 4. Human–AI Collaboration Doctrine

**Rule 4.1 — Dual Actors.** Humans and AI agents are both first-class engineering participants with defined, non-overlapping authority boundaries.

**Rule 4.2 — Human Authority.** Humans MUST retain final authority over requirements approval, architecture approval, release approval, gate waivers, and safety exceptions.

**Rule 4.3 — AI Execution.** AI agents MUST execute work only within scoped context, registered capabilities, and assigned autonomy levels.

**Rule 4.4 — No Self-Approval.** AI agents MUST NOT approve gates, waive exit criteria, or declare release readiness.

**Rule 4.5 — Scoped Context.** AI agents MUST NOT receive unbounded project context. Context MUST be scoped by the Context Manager per process and project.

**Rule 4.6 — Human Override.** Human decisions MUST override AI recommendations when conflict exists. Overrides MUST be recorded.

**Rule 4.7 — Escalation.** AI agents MUST escalate to a human owner when requirements are ambiguous, policy conflicts arise, or confidence is insufficient.

---

## 5. Architecture Principles

**Rule 5.1 — Subsystem Compliance.** All platform and project designs MUST conform to the approved Nexus OS subsystem architecture.

**Rule 5.2 — Policy Foundation.** Every subsystem and process MUST consult Policy & Access Control before acting.

**Rule 5.3 — Evaluation Gating.** The Workflow Kernel MUST NOT permit stage transitions without Evaluation Engine gate results.

**Rule 5.4 — Registered Capabilities.** The Execution Runtime MUST invoke only capabilities declared in the Capability Registry.

**Rule 5.5 — Observability Contract.** All subsystems MUST emit auditable events to the Observability & Audit System.

**Rule 5.6 — Earned Knowledge.** The Knowledge Base MUST accept only validated, approved inputs—not raw unverified process output.

**Rule 5.7 — Modularity.** Components MUST have explicit boundaries, defined interfaces, and unidirectional dependencies where applicable.

**Rule 5.8 — Domain Externality.** Domain logic MUST remain outside platform subsystems.

---

## 6. Workflow & Lifecycle Standards

**Rule 6.1 — Mandatory Workflow.** Every project MUST follow the official twelve-stage Nexus OS engineering workflow without skipping stages.

**Rule 6.2 — Stage Order.** Stages MUST be executed in sequence: Idea → Research → PRD → System Architecture → Engineering Planning → AI-Assisted Implementation → AI Review → Human Review → Testing & Evaluation → Deployment → Monitoring → Continuous Improvement.

**Rule 6.3 — Exit Criteria.** A stage MUST NOT be marked complete until all exit criteria for that stage are satisfied.

**Rule 6.4 — Gate Enforcement.** Advancement between stages MUST require passage of the applicable Engineering Gate as enforced by the Workflow Kernel.

**Rule 6.5 — No Retroactive Gates.** Gates MUST NOT be recorded as passed after downstream work has begun.

**Rule 6.6 — Failure Loopback.** Failed gates MUST return work to the failing or prior stage until criteria are met.

**Rule 6.7 — Deliverable Completeness.** Each stage MUST produce all required deliverables before exit.

---

## 7. Quality Bar & Definition of Done

**Rule 7.1 — Done Means Verified.** Work is Done only when it meets acceptance criteria, passes applicable review, and is recorded in the Artifact Repository.

**Rule 7.2 — Minimum Bar.** No artifact MAY be considered complete if it lacks traceability to a requirement, owner, and version.

**Rule 7.3 — No Partial Gates.** Exit criteria MUST be satisfied in full. Partial completion MUST NOT pass a gate unless an approved waiver is recorded.

**Rule 7.4 — Production Readiness.** Release-bound work MUST satisfy Human Review, AI Review clearance, and Testing & Evaluation thresholds before Deployment.

**Rule 7.5 — Documentation Included.** Done MUST include documentation sufficient for operation, review, and reuse by humans and agents.

---

## 8. Evaluation & Verification Standards

**Rule 8.1 — Evaluation Required.** All gate decisions MUST be produced by the Evaluation Engine or by human evaluators operating under defined criteria.

**Rule 8.2 — Criteria Before Execution.** Evaluation criteria MUST be defined before the work they govern is executed.

**Rule 8.3 — Objective Thresholds.** Evaluations MUST use explicit pass/fail thresholds. Subjective approval MUST NOT replace defined eval requirements.

**Rule 8.4 — Regression Detection.** Evaluations MUST compare against baselines where prior versions exist.

**Rule 8.5 — Remediation.** Failed evaluations MUST produce actionable remediation guidance and MUST block gate passage until resolved or formally waived.

**Rule 8.6 — Eval Archival.** All evaluation results MUST be archived in the Artifact Repository and linked to the Observability & Audit System.

---

## 9. Prompt, Skill & Agent Asset Standards

**Rule 9.1 — Registration Required.** All prompts, skills, agent roles, and procedures MUST be registered in the Capability Registry before production use.

**Rule 9.2 — Versioning.** Capability assets MUST be versioned. Breaking changes MUST increment version and MUST NOT silently replace prior versions.

**Rule 9.3 — Contract Definition.** Each capability MUST declare inputs, outputs, constraints, and approved use conditions.

**Rule 9.4 — Review Before Promotion.** New or modified capabilities MUST pass evaluation before promotion to approved status.

**Rule 9.5 — Deprecation.** Deprecated capabilities MUST be marked, MUST NOT be used in new work, and MUST retain a migration path until removal.

**Rule 9.6 — No Ad Hoc Capabilities.** Production processes MUST NOT invoke unregistered prompts, skills, or agent configurations.

**Rule 9.7 — Asset Integrity.** Capability assets MUST be stored in the Artifact Repository with full lineage.

---

## 10. Documentation as Engineering Infrastructure

**Rule 10.1 — Mandatory Documentation.** Every project MUST maintain documentation for requirements, architecture, decisions, operations, and evaluation.

**Rule 10.2 — Accuracy.** Documentation MUST reflect the current state of the system. Stale documentation MUST be treated as a defect.

**Rule 10.3 — Discoverability.** Documentation MUST be indexed and retrievable through the Knowledge Base or designated Artifact Repository paths.

**Rule 10.4 — Decision Records.** Significant technical and product decisions MUST be recorded as Architecture Decision Records or equivalent decision logs.

**Rule 10.5 — Agent Readability.** Documentation MUST be structured so AI agents can consume it reliably for scoped context.

**Rule 10.6 — No Undocumented Systems.** Systems without documentation MUST NOT pass Human Review or release gates.

---

## 11. Knowledge Management & Reuse Policy

**Rule 11.1 — Capture Validated Knowledge.** Outcomes from completed stages, retrospectives, and postmortems MUST be evaluated for promotion to the Knowledge Base.

**Rule 11.2 — Validation Required.** Only approved, validated knowledge MAY enter the Knowledge Base.

**Rule 11.3 — Reuse First.** Engineers and agents MUST consult the Knowledge Base before creating new patterns, capabilities, or designs.

**Rule 11.4 — Lineage.** Knowledge entries MUST reference source artifacts and decision records.

**Rule 11.5 — Deprecation.** Superseded knowledge MUST be marked deprecated and MUST point to its replacement.

**Rule 11.6 — No Duplication.** Duplicate knowledge entries SHOULD be consolidated. Redundant patterns MUST NOT proliferate unchecked.

---

## 12. Security & Privacy Requirements

**Rule 12.1 — Least Privilege.** All actors MUST operate with the minimum permissions required for their role.

**Rule 12.2 — Secrets Prohibition.** Secrets MUST NOT be stored in artifacts, prompts, skills, documentation, or version control.

**Rule 12.3 — Access Control.** Access to artifacts, capabilities, and knowledge MUST be enforced by Policy & Access Control.

**Rule 12.4 — Data Classification.** Sensitive data MUST be classified and handled according to platform policy before storage or transmission.

**Rule 12.5 — Audit Trail.** All security-relevant actions MUST be logged in the Observability & Audit System.

**Rule 12.6 — Vulnerability Response.** Known security defects MUST block release gates until remediated or formally waived by an authorized human owner.

---

## 13. AI Safety & Reliability Guardrails

**Rule 13.1 — Human Checkpoints.** High-risk actions MUST require human-in-the-loop approval as defined by Policy & Access Control.

**Rule 13.2 — Autonomy Limits.** AI agent autonomy MUST NOT exceed the level assigned for the current process and stage.

**Rule 13.3 — Failure Handling.** AI agents MUST fail safely. On uncertainty, agents MUST halt and escalate rather than produce unverified output.

**Rule 13.4 — Output Validation.** AI-generated outputs MUST be treated as unverified until passed through AI Review and, where required, Human Review.

**Rule 13.5 — No Unauthorized Action.** AI agents MUST NOT perform deployment, gate approval, policy changes, or scope expansion without explicit human authorization.

**Rule 13.6 — Reliability Targets.** Systems MUST define reliability expectations in the PRD and MUST be evaluated against them before release.

**Rule 13.7 — Drift Monitoring.** Production AI behavior MUST be monitored for eval drift during the Monitoring stage and beyond.

---

## 14. Testing Strategy & Test Hierarchy

**Rule 14.1 — Test Plan Required.** Every project MUST define a test and evaluation plan before Implementation begins.

**Rule 14.2 — Test Hierarchy.** Projects MUST employ a layered test strategy appropriate to the work: unit verification, integration verification, eval-based verification, regression verification, and smoke verification.

**Rule 14.3 — Mandatory Pre-Release Testing.** Release-bound work MUST NOT proceed to Deployment without passing all mandatory test and eval suites defined in the plan.

**Rule 14.4 — Traceability.** Tests MUST map to requirements or acceptance criteria.

**Rule 14.5 — Regression Suite.** Projects with prior releases MUST maintain regression coverage for critical behavior.

**Rule 14.6 — Eval for AI Behavior.** AI-driven behavior MUST include eval-based verification beyond traditional unit tests.

**Rule 14.7 — Failure Blocking.** Unresolved release-blocking test or eval failures MUST block Gate G8 (Release Readiness).

---

## 15. Code Review & Change Control

**Rule 15.1 — Review Required.** All implementation artifacts MUST pass AI Review and Human Review before release.

**Rule 15.2 — No Self-Merge.** Authors MUST NOT be the sole approver of their own release-bound work.

**Rule 15.3 — Finding Resolution.** Blocker and major review findings MUST be resolved or formally waived before gate passage.

**Rule 15.4 — Traceable Changes.** All changes MUST link to requirements, decisions, or approved plan items.

**Rule 15.5 — Elevated Scrutiny.** Changes to capabilities, eval harnesses, policy rules, and security-sensitive paths MUST receive elevated review.

**Rule 15.6 — Change Record.** Significant changes MUST be recorded in the Artifact Repository with version history.

---

## 16. Observability, Logging & Auditability

**Rule 16.1 — Universal Logging.** All subsystems, agents, and workflows MUST emit events to the Observability & Audit System.

**Rule 16.2 — Action Traceability.** Every gate decision, review outcome, deployment, and override MUST be traceable to an actor, timestamp, and rationale.

**Rule 16.3 — Immutable Audit Record.** Audit records MUST NOT be altered or deleted except under governed retention policy.

**Rule 16.4 — Incident Correlation.** Production incidents MUST be correlatable to pre-release eval results and deployment records.

**Rule 16.5 — Retention Compliance.** Log and audit retention MUST comply with Policy & Access Control.

---

## 17. Dependency & Tooling Policy

**Rule 17.1 — Approved Tooling.** Projects MUST use tooling approved for Nexus OS unless an exception is granted.

**Rule 17.2 — Dependency Justification.** New dependencies MUST be justified and MUST NOT introduce unmanaged risk.

**Rule 17.3 — Pinning.** Dependencies MUST be pinned to known versions for release-bound work.

**Rule 17.4 — Abandonment Criteria.** Dependencies that are unmaintained or non-compliant MUST be flagged and MUST be replaced or waived with documented rationale.

**Rule 17.5 — Toolchain Consistency.** Projects SHOULD align with platform-standard toolchains to preserve reuse and auditability.

---

## 18. Performance, Cost & Efficiency Standards

**Rule 18.1 — Defined Expectations.** Performance and cost expectations MUST be declared in the PRD or architecture for user-facing and operational systems.

**Rule 18.2 — Pre-Release Assessment.** Release-bound systems MUST be evaluated for performance and cost against declared expectations.

**Rule 18.3 — No Unbounded Cost.** Systems MUST NOT deploy without defined cost boundaries or monitoring for cost anomalies.

**Rule 18.4 — Efficiency Review.** Inefficient designs that violate declared expectations MUST be remediated or waived before release.

---

## 19. Backward Compatibility & Migration Rules

**Rule 19.1 — Compatibility Declaration.** Breaking changes to platform standards, templates, or capabilities MUST be declared before adoption.

**Rule 19.2 — Migration Path.** Breaking changes MUST include a documented migration path for dependent projects.

**Rule 19.3 — Version Coexistence.** Where feasible, prior versions SHOULD remain accessible during a defined transition period.

**Rule 19.4 — No Silent Breakage.** Projects MUST NOT be broken by platform changes without notice and migration guidance.

---

## 20. Incident Response & Postmortem Standards

**Rule 20.1 — Incident Ownership.** Production incidents MUST have a designated human incident owner.

**Rule 20.2 — Response Timeliness.** Critical incidents MUST be triaged and mitigated according to platform incident response standards.

**Rule 20.3 — Blameless Postmortem.** Significant incidents MUST produce a blameless postmortem with root cause, timeline, and corrective actions.

**Rule 20.4 — Knowledge Promotion.** Postmortem findings MUST be evaluated for promotion to the Knowledge Base.

**Rule 20.5 — Gate Impact.** Unresolved critical incidents attributable to a release MUST block stabilization gate passage.

---

## 21. Decision-Making Framework

**Rule 21.1 — ADR Requirement.** Significant architectural decisions MUST be recorded as ADRs before implementation proceeds.

**Rule 21.2 — Decision Authority.** Decision authority MUST follow defined roles in Section 24. Decisions MUST NOT bypass accountable owners.

**Rule 21.3 — Dispute Escalation.** Unresolved technical disputes MUST escalate to the accountable engineering owner.

**Rule 21.4 — Open Decisions.** Unresolved decisions MUST be logged. Implementation MUST NOT proceed on unresolved blocker decisions.

**Rule 21.5 — Reversibility.** Reversible decisions SHOULD be made quickly. Irreversible decisions MUST receive architecture-level review.

---

## 22. Technical Debt Policy

**Rule 22.1 — Debt Definition.** Technical debt is any known deviation from standards, architecture, or quality bar that is accepted temporarily.

**Rule 22.2 — Explicit Recording.** All accepted debt MUST be recorded with owner, rationale, and remediation plan.

**Rule 22.3 — No Silent Debt.** Debt MUST NOT accumulate without documentation.

**Rule 22.4 — Release Limits.** Release-blocking debt MUST be resolved or waived before Gate G8.

**Rule 22.5 — Paydown.** Debt MUST be reviewed during Continuous Improvement and MUST be prioritized for remediation.

---

## 23. Project Bootstrap & Template Compliance

**Rule 23.1 — Template Required.** All new projects MUST be bootstrapped from an approved Nexus OS project template.

**Rule 23.2 — Minimum Structure.** Bootstrapped projects MUST include required documentation placeholders, eval setup, agent rules, and workflow tracking.

**Rule 23.3 — Compliance from Day One.** Projects MUST comply with this Constitution from initialization. Compliance MUST NOT be deferred.

**Rule 23.4 — Template Currency.** Project templates MUST be maintained to reflect current Constitution and workflow requirements.

**Rule 23.5 — No Rogue Scaffolding.** Custom project structures MUST NOT bypass required template elements without an approved exception.

---

## 24. Roles, Ownership & Accountability

**Rule 24.1 — Accountable Engineering Owner.** Every project MUST designate one accountable engineering owner with final authority on engineering and release decisions.

**Rule 24.2 — Product Owner.** Every project MUST designate one product owner with final authority on requirements and scope.

**Rule 24.3 — Platform Ownership.** Nexus OS platform assets MUST have designated owners responsible for maintenance and compliance.

**Rule 24.4 — No Orphan Artifacts.** All artifacts, capabilities, and knowledge entries MUST have a named owner.

**Rule 24.5 — Delegation.** Delegation MUST NOT transfer accountability. Delegates act on behalf of owners; owners remain accountable.

**Rule 24.6 — Role Separation.** The same actor MUST NOT hold conflicting approval roles for a single gate unless explicitly permitted by policy.

---

## 25. Exception Process & Amendment Procedure

**Rule 25.1 — Exception Required.** Any deviation from this Constitution MUST follow the formal exception process.

**Rule 25.2 — Exception Documentation.** Exceptions MUST record scope, rationale, owner, expiry date, and compensating controls.

**Rule 25.3 — Human Approval.** Exceptions MUST be approved by an authorized human owner under Policy & Access Control. AI agents MUST NOT grant exceptions.

**Rule 25.4 — Temporary by Default.** Exceptions SHOULD be time-bound. Permanent exceptions MUST be rare and MUST trigger Constitution review.

**Rule 25.5 — Amendment Authority.** Amendments to this Constitution MUST be proposed in writing, reviewed, and ratified by designated platform governance authority.

**Rule 25.6 — Version Recording.** All amendments MUST be recorded in Section 28 (Version History).

---

## 26. Enforcement & Compliance Mechanism

**Rule 26.1 — Gate Enforcement.** The Workflow Kernel MUST enforce Engineering Gates according to this Constitution.

**Rule 26.2 — Policy Enforcement.** Policy & Access Control MUST enforce permissions, autonomy limits, and exception validity.

**Rule 26.3 — Automated Checks.** Compliance checks SHOULD be automated where feasible. Manual attestation MUST NOT replace verifiable checks when automation exists.

**Rule 26.4 — Non-Compliance Blocking.** Non-compliant work MUST NOT pass gates or reach Deployment.

**Rule 26.5 — Audit Review.** Compliance MUST be auditable through the Observability & Audit System at any time.

**Rule 26.6 — Continuous Compliance.** Compliance MUST be maintained throughout the lifecycle, not verified only at release.

---

## 27. Glossary & Canonical Definitions

| Term | Definition |
|------|------------|
| **Accountable Engineering Owner** | Human with final authority on engineering quality and release decisions for a project. |
| **AI Agent** | An automated actor executing engineering work under scoped context, registered capabilities, and policy constraints. |
| **Artifact** | Any versioned engineering object produced or consumed on the platform. |
| **Artifact Repository** | Subsystem providing persistent storage, identity, versioning, and lineage for artifacts. |
| **Capability** | A registered skill, prompt, procedure, or agent role invokable by the Execution Runtime. |
| **Capability Registry** | Subsystem cataloging all approved capabilities and their contracts. |
| **Context Manager** | Subsystem maintaining scoped active working state for in-flight work. |
| **Engineering Gate** | A mandatory checkpoint enforced by the Workflow Kernel before stage advancement. |
| **Evaluation Engine** | Subsystem measuring and judging outputs against defined quality criteria. |
| **Exception** | A documented, time-bound, human-approved deviation from a Constitutional rule. |
| **Execution Runtime** | Subsystem running isolated human and agent engineering processes. |
| **Knowledge Base** | Subsystem storing validated, reusable organizational engineering knowledge. |
| **Observability & Audit System** | Subsystem recording traceable history of all platform activity. |
| **Policy & Access Control** | Foundational subsystem enforcing permissions, constraints, and compliance rules. |
| **PRD** | Product Requirements Document defining what a product must accomplish without prescribing implementation. |
| **Scheduler & Orchestrator** | Subsystem allocating work across humans and agents based on priority and capacity. |
| **Workflow Kernel** | Subsystem coordinating lifecycle states, transitions, and gate enforcement. |

---

## 28. Version History

| Version | Date | Author | Summary |
|---------|------|--------|---------|
| 1.0.0 | 2026-07-17 | Nexus OS Chief Architect | Initial ratification of the Engineering Constitution |

---

*This Constitution is the supreme governing document of Nexus OS. All humans, AI agents, workflows, projects, skills, prompts, and subsystems MUST comply.*
