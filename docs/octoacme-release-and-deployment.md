# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- Named release owner confirmed (Release Manager or Project Manager)
- QA Lead sign-off captured with unresolved risks documented
- Support/Customer Success enablement prepared for known issues and escalation paths
- Role handoffs validated using [Roles & Personas](./octoacme-roles-and-personas.md)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] QA Lead validates staging results and signs off
- [ ] Deploy to production (automated pipeline preferred)
- [ ] DevOps Engineer verifies pipeline and monitoring health
- [ ] Run post-deploy verifications
- [ ] Support/Customer Success receives release notes and escalation guidance
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items
  - Communicate escalation status using [Risk Management & Communication](./octoacme-risks-and-communication.md)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
