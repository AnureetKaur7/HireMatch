# Member 1 — Authentication & User Management

Own authentication, identity, role access and auth UI.

## Your owned files (primary responsibility)
- `server/routes/auth.js`
- `server/middleware/auth.js`
- `server/models/User.js`
- `client/src/pages/Auth.jsx`
- `client/src/AuthContext.jsx`
- `client/src/components/Navbar.jsx`
- `client/src/App.jsx`
- `client/src/api.js`

## Work to complete
- [ ] Email/password registration and login
- [ ] Google sign-in endpoint and frontend integration (if configured)
- [ ] bcrypt password hashing and JWT creation/verification
- [ ] Candidate/recruiter roles and protected routes
- [ ] Login/logout state and navigation
- [ ] Test authentication, invalid credentials and role restrictions

## CSS responsibility
Authentication screens, navbar, shared buttons and auth-related responsive styling.

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
