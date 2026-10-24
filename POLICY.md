# Governance Policy — Aodı Akdıro Data OS

Adopt, sign, then activate into the **🛡️ Governance Policy** module checklist (the same 18 items rated high / med / low live there).

**Ground rule:** approval first, activation second; rejections documented with a reason.

## PII and access (high risk)
1. Separate personal data from operational data in independent tables.
2. Mask personal identifiers in every analytics layer.
3. Encrypt sensitive columns in transit and at rest.
4. Least privilege: the minimum role that serves the task.
5. Dated query logs on sensitive tables.
6. Consent merged into every import request that touches a user.
7. No re-identification rules for public research — written and enforced.

## Operations (high/med)
8. Backups with a tested, documented restore.
9. Table owners with written edit/approve roles.
10. Monthly spend cap with early alerting.
11. Query time caps with automatic cancellation.
12. Interactive analytics never runs against the production store directly.
13. Quarterly restore test from an old backup.
14. Unified metric dictionary signed by metric owners.
15. Quarterly access review with leavers removed.

## Process discipline (med/low)
16. Export rules written and shared — where data may leave and why.
17. Incident escalation with a channel and a reporting window.
18. Quarterly policy review with a signed change log.

Adopted by: ______________  Date: __________  Scope: __________
