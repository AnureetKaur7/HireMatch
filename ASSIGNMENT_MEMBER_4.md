# Member 4 — Recruiter Dashboard & Recruitment Workflow

Own recruiter-facing job/applicant management, stage transitions and integration testing.

## Your owned files (primary responsibility)
- `server/routes/jobs.js (POST /, PATCH /:id/close, GET /mine and GET /:id/applicants recruiter portions; coordinate with Member 2)`
- `server/routes/applications.js (PATCH /:id/stage portion; coordinate with Member 3)`
- `server/utils/stages.js`
- `server/seed.js`
- `server/server.js`
- `client/src/pages/Dashboard.jsx`
- `client/src/pages/Applicants.jsx`
- `client/src/components/StageBar.jsx (integration/use only; component implementation owned by Member 3)`

## Work to complete
- [ ] Recruiter job creation, listing/ownership and close-job workflow
- [ ] Recruiter dashboard and job/applicant counts
- [ ] Applicant list and candidate/match details for recruiter
- [ ] Recruitment stage updates and server-side valid-transition rules
- [ ] Seed/demo data and local integration setup
- [ ] Integration test candidate and recruiter end-to-end flows
- [ ] Test recruiter ownership checks and invalid stage transitions

## CSS responsibility
Recruiter dashboard, job management controls, applicant cards, stage workflow and responsive testing.

## Important collaboration rules
- Each archive contains the complete clean project so you can understand, run and test the integrated application. It does NOT mean you own every file.
- Edit your owned files. For files marked “coordinate”, agree on route boundaries and communicate before editing; do not overwrite another member’s changes.
- Keep shared changes small and commit them with clear messages. Merge work into one common Git repository/branch managed by the team.
- Do not commit `.env` files, passwords, database URLs, OAuth secrets or JWT secrets. Copy `.env.example` to `.env` locally and fill in your own authorized values.
- Do not include `node_modules` or `.git` in submissions. Run `npm install` inside both `server` and `client` folders.

## Run the full project
1. In `server`, copy `.env.example` to `.env`, configure MongoDB and secrets, then run `npm install` and `npm run dev` (or the script specified in `server/package.json`).
2. In `client`, copy `.env.example` to `.env`, configure values if needed, then run `npm install` and `npm run dev`.
3. Run the seed command only if the team agrees to use the demo database; check `README.md` first.

## Evidence for evaluation
- Be ready to explain your implementation, important functions, APIs, database operations, validation/security decisions, one challenge and its solution.
- Demonstrate your feature in the running application and provide test cases/results.
