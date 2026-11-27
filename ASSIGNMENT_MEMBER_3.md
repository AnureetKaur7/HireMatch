# Member 3 — Candidate Profile & Candidate Applications

Own candidate profile data, profile editing, applying and candidate application tracking.

## Your owned files (primary responsibility)
- `server/routes/profile.js`
- `server/routes/applications.js (POST / and GET /me portions; coordinate stage endpoint with Member 4)`
- `server/models/CandidateProfile.js`
- `server/models/Application.js`
- `client/src/pages/Profile.jsx`
- `client/src/pages/MyApplications.jsx`
- `client/src/components/StageBar.jsx (build reusable display component; coordinate its use with Member 4)`

## Work to complete
- [ ] Candidate profile schema and profile read/update APIs
- [ ] Candidate skills, headline, experience and expected CTC
- [ ] Application submission and server-side experience eligibility check
- [ ] Prevent duplicate applications using the compound unique index on job + candidate
- [ ] Candidate application history and status display
- [ ] Build reusable application stage display component
- [ ] Test profile updates, eligibility, duplicate submissions and application history

## CSS responsibility
Candidate profile, skills selector, profile forms, application list and status/stage display styling.

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
