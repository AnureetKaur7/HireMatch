# Member 2 — Job Management, Discovery & Skill Matching

Own job discovery and the candidate-facing job search/matching experience.

## Your owned files (primary responsibility)
- `server/routes/jobs.js (public GET / and GET /:id portions; coordinate recruiter endpoints with Member 4)`
- `server/models/Job.js`
- `server/utils/match.js`
- `client/src/pages/Jobs.jsx`
- `client/src/pages/JobDetail.jsx`
- `client/src/components/JobCard.jsx`
- `client/src/components/MatchRing.jsx`

## Work to complete
- [ ] Job schema and job detail retrieval
- [ ] Job listing/search by role and location
- [ ] Filters for work mode, experience, CTC and skills
- [ ] Pagination using page and limit query parameters
- [ ] Skill-match percentage and missing-skills calculation
- [ ] Job cards, job detail page and match display
- [ ] Test search, filters, pagination and match edge cases

## CSS responsibility
Job cards, job listings, filters, pagination, job details and match ring styling.

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
