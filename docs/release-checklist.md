# Release Checklist

Purpose: A concise checklist to standardize pre-release, release, and post-release activities.

Pre-release
- [ ] All PRs merged with passing CI and security scans
- [ ] Acceptance criteria met and verified in staging
- [ ] Release notes drafted and reviewed by Technical Writer
- [ ] Rollback plan documented and tested (where applicable)
- [ ] Monitoring/dashboards for key metrics are in place
- [ ] Stakeholders informed of release window and impact
- [ ] Release Manager signs off on readiness

Release
- [ ] Deploy to staging and run smoke tests
- [ ] Run integration and end-to-end critical path checks
- [ ] Schedule production deployment (release window confirmed)
- [ ] Notify on-call and Support Owner
- [ ] Execute production deployment via automated pipeline
- [ ] Monitor deploy progress and respond to failures

Post-release
- [ ] Run post-deploy verifications and smoke tests
- [ ] Validate key success metrics (basic sanity checks)
- [ ] Announce release to stakeholders and update status page
- [ ] Run a short post-release review: issues, regressions, action items
- [ ] If incident occurred, link postmortem and action items to the release notes

Rollback & mitigation
- If rollback is required:
  - [ ] Execute rollback plan (automated or manual steps documented)
  - [ ] Notify stakeholders and Support Owner
  - [ ] Triage root cause and create action items

See also: docs/checklists/deployment-and-rollback.md for detailed deployment steps.
