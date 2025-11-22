# Release Checklist

Use this checklist to ensure a smooth, safe release process. Complete all applicable items for each release.

---

## Pre-Release Preparation

### Requirements & Quality
- [ ] All acceptance criteria met and verified
- [ ] All PRs merged to release branch
- [ ] CI pipeline passing (all environments)
- [ ] Security scans passing (no critical/high vulnerabilities)
- [ ] Code review completed for all changes
- [ ] Unit tests passing (coverage meets threshold)
- [ ] Integration tests passing
- [ ] End-to-end smoke tests passing

### Documentation & Communication
- [ ] Release notes drafted and reviewed
- [ ] Changelog updated with all changes
- [ ] User-facing documentation updated (if applicable)
- [ ] API documentation updated (if applicable)
- [ ] Known issues documented
- [ ] Stakeholders notified of upcoming release
- [ ] Support/CS team notified and briefed

### Infrastructure & Planning
- [ ] Deployment plan documented and reviewed
- [ ] Rollback plan documented and tested
- [ ] Database migrations tested (if applicable)
- [ ] Configuration changes documented
- [ ] Feature flags configured (if applicable)
- [ ] Snapshot/backup taken (if needed)
- [ ] Incident contacts list updated and verified
- [ ] On-call schedule confirmed for release window

---

## During Release

### Staging Validation
- [ ] Deploy to staging environment
- [ ] Staging smoke tests executed and passing
- [ ] Database migrations applied successfully (staging)
- [ ] Performance benchmarks acceptable
- [ ] Security scanning completed in staging
- [ ] Stakeholder approval to proceed to production

### Production Deployment
- [ ] Maintenance window announced (if applicable)
- [ ] Snapshot/backup confirmed before deployment
- [ ] Production deployment initiated
- [ ] Database migrations applied (if applicable)
- [ ] Configuration changes applied
- [ ] Feature flags enabled as planned
- [ ] Application health checks passing

---

## Post-Release Verification

### Validation & Monitoring
- [ ] Production smoke tests passing
- [ ] Key user flows verified manually
- [ ] Error rates within acceptable range
- [ ] Performance metrics within acceptable range
- [ ] Monitoring dashboards reviewed
- [ ] Logs reviewed for errors or warnings
- [ ] User-reported issues triaged (if any)

### Communication & Documentation
- [ ] Release announcement sent to stakeholders
- [ ] Release notes published to users
- [ ] Support/CS team notified of successful release
- [ ] Incident contacts reminded and on standby
- [ ] Post-release status report sent to stakeholders

### Cleanup & Follow-up
- [ ] Old deployment artifacts cleaned up (if applicable)
- [ ] Temporary feature flags removed (if applicable)
- [ ] Release retrospective scheduled
- [ ] Known issues tracked in backlog
- [ ] Metrics baseline captured for success tracking

---

## Rollback Procedure (If Needed)

If critical issues are discovered:
- [ ] Incident declared and team notified
- [ ] Rollback decision approved by [specify role]
- [ ] Rollback procedure executed per plan
- [ ] Verification that rollback successful
- [ ] Stakeholders notified of rollback
- [ ] Post-mortem scheduled to review issues

---

## Sign-off

**Release Manager:** _________________  
**Date/Time:** _________________  

**Project Manager:** _________________  
**Date/Time:** _________________  

**Deployment Completed:** _________________  
**Post-Release Verified:** _________________
