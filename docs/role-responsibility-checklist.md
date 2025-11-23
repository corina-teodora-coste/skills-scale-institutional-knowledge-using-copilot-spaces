```markdown
# Role & Responsibility Checklist (planning / release)

Use this checklist during planning and pre-release to ensure owners are assigned and cross-cutting concerns are covered.

## Before planning is complete
- [ ] Product Manager identified and success metrics defined
- [ ] Project Manager / Delivery lead assigned
- [ ] Development owner(s) assigned
- [ ] QA owner assigned and test approach agreed
- [ ] DevOps/SRE contact identified for deployment & monitoring
- [ ] Security contact identified (if feature touches sensitive data or auth)
- [ ] UX/Design owner identified (if user-facing changes)
- [ ] Data analyst / BI owner identified (if metrics/analytics required)
- [ ] Technical writer / documentation owner identified
- [ ] Accessibility specialist engaged (if applicable)
- [ ] Legal / Compliance engaged (if applicable)
- [ ] Customer Success / Support lead notified for post-release handling

## Pre-release readiness (complete before scheduling deployment)
- [ ] All acceptance criteria met
- [ ] CI passing and security scans green
- [ ] Observability/metrics instrumented and dashboard(s) prepared
- [ ] Runbooks and on-call contact info updated
- [ ] Documentation & release notes drafted and reviewed
- [ ] Accessibility checks passed or known issues documented
- [ ] Legal/compliance sign-off obtained (if required)
- [ ] Release Manager confirmed deployment window and rollback plan
- [ ] Support playbook prepared for known user-impact scenarios

## Post-release
- [ ] Post-deploy smoke tests executed and green
- [ ] Monitoring for errors/latency reviewed within agreed window
- [ ] Customer feedback / support tickets triaged and escalated as needed
- [ ] Release outcome and metrics reported to stakeholders

Notes:
- If a role is not needed for a particular project, mark it as N/A and provide rationale.
- Capturing owners explicitly reduces handoff friction and speeds decision making.
```
