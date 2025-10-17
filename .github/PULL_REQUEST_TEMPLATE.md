# Backend Pull Request Template

**Title:** <short, imperative summary> (e.g. "Add user search endpoint")

**Ticket / Issue**
- Closes: # (issue number) / Fixes: # / Related: #

## Summary
- One-sentence summary of the change.
- High-level rationale — why this change is needed.

## Key changes
- Bullet list of the most important changes (endpoints, DB schema, public APIs, libraries updated).

## Type of change (check all that apply)
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation
- [ ] Refactor
- [ ] Tests
- [ ] CI/CD
- [ ] Release
- [ ] Other — describe: ______

## Breaking changes
- [ ] Yes — describe breaking change(s) and migration plan
- [ ] No

## Database / Migrations
- [ ] None
- [ ] Migration(s) added — describe migration steps and how to run them (e.g., `rails db:migrate`)
- Backward compatibility notes:

## API / Contracts
- [ ] Public API changed — update OpenAPI/Swagger: yes/no
- Endpoint changes (paths, request/response examples, auth changes):

## Security considerations
- Any new secrets, token scope changes, user data exposure, or required security review.

## Testing performed
**Type:**
- [ ] Automated (unit / integration / e2e) — list affected test suites and commands to run (e.g., `yarn test:unit`)
- [ ] Manual — describe scenarios and verification steps

**Details:**  
Describe how the changes were tested (commands, scenarios, or attach screenshots if manual).

## How to run locally (exact commands)
- Clone/checkout:
  - `git checkout -b <branch-name>`
- Setup:
  - e.g., `cp .env.example .env` and set DB_URL / credentials
- Run:
  - e.g., `./gradlew test`, `docker-compose up -d`, `pytest tests/`
- API test commands / curl examples:
  - `curl -X POST "http://localhost:3000/api/v1/..." -d '{...}'`

## Performance / Load
- Any performance benchmarks or known impacts; include measurements if available.

## Checklist (self-review)
- [ ] I have reviewed my PR
- [ ] I removed unnecessary logs and commented-out code
- [ ] I ran the test suite locally and all tests pass
- [ ] I added/updated tests for my changes
- [ ] I updated documentation where needed (README, API docs)
- [ ] I updated CHANGELOG.md / Release notes if applicable
- [ ] I updated OpenAPI/Swagger (if API changed)
- [ ] I added/updated database migrations and included rollback notes
- [ ] I considered security implications

## Notes for the reviewer
- Anything the reviewer should focus on, tricky areas, or files to ignore.
- Suggested reviewers or teams: @team/backend, @team-api

## Screenshots / Recordings (optional)
- Attach screenshots, logs, or GIFs demonstrating UI/behavior (if applicable)

## Other notes
- Deployment instructions, rollout plan, or backward-compatibility notes.
