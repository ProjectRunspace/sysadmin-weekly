# IT Outage Postmortem

*This is a blameless postmortem. The goal is root cause and prevention, not attribution. We document what broke and why so it does not break the same way again. We do not document who to punish.*

## Incident Details

- Incident ID: (Ex. INC-2026-0042)
- Date of Incident: (Ex. 2026-07-18)
- Severity: SEV1 / SEV2 / SEV3
  - SEV1: Major outage, customer-facing or revenue-impacting, all-hands response
  - SEV2: Significant degradation or internal outage, scoped response team
  - SEV3: Minor or single-user impact, handled by one or two people
- Status: Draft / Final

## Report by:

Name, Job Title, Team Name

-INSERT RESPONSE-

## Review Participants

Everyone who took part in the review (not just responders). Note system owners and any independent reviewers.

-INSERT RESPONSE-

## What Happened

TL;DR summary of the incident

-INSERT RESPONSE-

## Impact Summary

- First Noticed: (Ex. 12:03 AM UTC, automated alert)
- Detected / Confirmed: (Ex. 12:10 AM UTC)
- Mitigated: (Ex. 1:46 AM UTC)
- Resolved: (Ex. 2:17 AM UTC)
- Total Duration: (Ex. 2h 14m)
- Affected Services: (Ex. Public website, API gateway...etc)
- User Impact: (Ex. 503 errors for 18% of traffic during outage window)
- Customer-Facing? Yes/No

## Timeline

Use a consistent timezone for every entry. UTC is recommended for distributed or after-hours incidents.

- `12:03 AM UTC` - Monitoring alert triggered
- `12:10 AM UTC` - Initial triage began
- ...

## Root Cause

What were the primary cause(s)? Stick to what you can verify, not the first thing that looked like fault.

-INSERT RESPONSE-

## Contributing Factors

Were there other issues that made this worse? (Ex. Missing alert, wrong runbook, undertrained staff, legacy system quirks)

-INSERT RESPONSE-

## (Optional) SLA (Service Level Agreement) Impact

Outage was / was not within defined SLA window - Explain

-INSERT RESPONSE-

## (Optional) Compliance Framework Implications (If any)

What framework violation occured? (Ex. HIPAA control XYZ)

-INSERT RESPONSE-

## Security Related Incident?

Yes or No? Explain

-INSERT RESPONSE-

## Fix Implemented

What was done to resolve the issue?

-INSERT RESPONSE-

- [ ] Temporary workaround
- [ ] Permanent fix deployed
- [ ] Follow-up change(s) scheduled

If follow-ups are scheduled what are they? And When?

-INSERT RESPONSE-

## Lessons Learned

### Monitoring

- [ ] Alert triggered appropriately?
- [ ] Escalation procedures effective?

### Communication

- [ ] Stakeholders notified in time?
- [ ] Response team aligned?

### Documentation

- [ ] Runbook useful?
- [ ] Diagrams or workflows outdated?

### Process / Human Factors

- [ ] Better onboarding or training needed?
- [ ] Were roles clearly defined?

Add any additional insights below:

-INSERT RESPONSE-

## Action Items

| Owner | Task | Due Date | Status |
|-------|------|----------|--------|
| Alice | Patch server config | 2026-07-20 | ☐ |
| Bob | Update internal docs | 2026-07-21 | ☐ |
| Carol | Run RCA review | 2026-07-25 | ☐ |

## Follow-Up / Close-Out

The follow-through is the whole point. An action item that quietly slips for three sprints means this review was wasted.

- Next Review Date: (Ex. 2026-07-25)
- Loop Owner: (Who confirms every action item above is actually closed?)
- Close-Out Status: Open / Closed

-INSERT RESPONSE-
