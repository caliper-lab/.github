## What and why

<!-- One or two sentences. Link the ticket: EA-123 -->

Jira:

## How it was tested

<!-- Commands you ran, screenshots, curl calls. -->

## Security impact

<!-- "None" is a valid answer, but say why. -->

- [ ] No secrets, tokens, real customer data or `.env` in the diff
- [ ] New or changed routes: authenticated, permission checked on the server, tenant from the session
- [ ] Inputs validated; SQL parameterized; no new writes to read-only sources (FBS, SGA, Sheets, Colppy)
- [ ] New env vars added to `.env.example`
- [ ] Schema change has a migration that runs from zero
- [ ] Tests added for the fix / new behavior (auth + tenant tests for new routes)
- [ ] `AGENTS.md` / README updated if commands, env vars or data flows changed

<!-- Standards: .standards/STANDARDS.md -->
