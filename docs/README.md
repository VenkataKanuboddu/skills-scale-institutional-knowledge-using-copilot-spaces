# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents. The README below provides a short summary of our approach and direct links to each document to help new teammates find the guidance they need.

## Overview
OctoAcme runs projects through a lightweight, stage-based lifecycle: Initiation, Planning, Execution, Release, and Close/Retrospective. Initiation uses a one‑pager to validate the problem, stakeholders, and success metrics. Planning turns approved work into a prioritized backlog with acceptance criteria, estimates, and an explicit Definition of Done. Execution uses iterative delivery with project boards and a disciplined PR workflow; releases are governed by pre-release checks, smoke tests, and rollback plans. Retrospectives capture learnings and convert them into actionable backlog items.

## Key Workflows & Roles
Work is tracked via a project board (Backlog → Ready → In Progress → In Review → QA → Done) and small, CI-backed pull requests that include acceptance criteria and an issue link. Core personas are defined so responsibilities are clear: Product Managers (PdM) drive outcomes and prioritization, Project Managers (PM) coordinate delivery and communications, Developers implement and test, QA validates acceptance criteria, and Stakeholders provide input and approvals. Risk management is continuous—risks are logged, assessed, and reviewed regularly with a clear escalation path from team → PM → Product Lead → Sponsor.

## Communication & Quality
Team cadence includes daily standups for blockers, a weekly delivery sync for progress and dependencies, sprint demos/reviews, and periodic PM+PdM alignment. Stakeholder updates use a consistent weekly status template and a single source-of-truth document for status. Quality practices emphasize automated testing (unit, integration, security scanning, and smoke tests) plus manual QA where necessary; releases follow a deployment checklist and include rollback/incident playbooks. Retrospectives prioritize 2–3 action items and track their implementation via the backlog.

## Documents
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-roles-and-personas.md

## How to use
- Read the overview first, then open the document relevant to your role or current project phase.
- Link this README from the repo root or contributor onboarding doc for quick access.
- To propose updates to these docs, use the Add Content to Project Management Process Docs issue template in .github/ISSUE_TEMPLATE/.
