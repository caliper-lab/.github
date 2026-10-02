# Security policy

## Reporting a vulnerability

Do **not** open a public issue or PR for a vulnerability. Write to
**lautaro@caliper-systems.com** with:

- the affected repo, URL or app,
- what you found and how to reproduce it,
- the impact you think it has.

You'll get an answer within 2 business days. Critical issues (data exposure,
auth bypass, leaked secrets) are fixed or mitigated within 48 hours.

## If you find a leaked secret

1. Tell the repo owner right away.
2. The secret is **rotated first**, then removed from code and, if needed, from git history.
3. It's logged as a Critical finding in the repo's `AUDIT.md` and in Jira.

## Standards

All repos follow `.standards/STANDARDS.md` (from `caliper-lab/platform-standards`).
