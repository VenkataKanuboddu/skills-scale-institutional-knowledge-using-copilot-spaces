# Deployment & Rollback Checklist (detailed)

Purpose: Detailed step-by-step guide to perform a deployment and execute rollback if needed.

Before deployment
1. Verify staging validation
  - Confirm all staging tests passed
  - Smoke test critical user journeys
  - Confirm feature flags and toggles state
2. Prepare deployment window
  - Notify stakeholders and on-call
  - Confirm backup/snapshot availability (if applicable)
3. Verify monitoring and alerting
  - Confirm dashboards present and baseline metrics recorded
  - Confirm alerting rules and on-call contact

Deployment steps
1. Run pre-deploy scripts (migrations, canary config)
2. Trigger CI/CD pipeline for staging dry-run
3. Trigger production deployment via the pipeline
4. Monitor pipeline steps for failures
5. Run health checks and smoke tests post-deploy
6. Observe metrics for error rate, latency, and system load

Rollback steps
- If automated rollback is available, trigger it immediately and follow the post-rollback verification steps below.
- If manual rollback required:
  1. Stop the rollout
  2. Redeploy last known-good artifact
  3. Reconfigure any feature flags back to safe state
  4. Verify system health

Post-rollback verification
- Validate that service is restored to expected state
- Confirm reduced error rates and normal latency
- Communicate status to stakeholders and Support Owner
- Create a post-incident action item to investigate root cause

Notes
- Always practice rollback in staging before using in production.
- Keep rollback instructions versioned alongside release notes.
