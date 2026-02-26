# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Release Roles
- **Release Manager**: Owns the release schedule and go/no-go decision. Coordinates cutover logistics, stakeholder communications, and post-release reviews.
- **Support/SRE Lead**: Validates operational readiness (monitoring, on-call, runbooks) and is the first point of contact during post-deploy incidents.

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted (coordinated with Technical Writer)
- Rollback / mitigation plan documented and reviewed with Support/SRE Lead
- Smoke tests prepared

## Release Coordination Checklist
- [ ] Release Manager has confirmed the release window with stakeholders
- [ ] Support/SRE Lead has reviewed the deployment plan and runbooks
- [ ] Release notes and stakeholder communications drafted and approved
- [ ] On-call rotation confirmed for the deployment window

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (Release Manager)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
