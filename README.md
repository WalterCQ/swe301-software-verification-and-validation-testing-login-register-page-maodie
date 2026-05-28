# SWE301 SecureApp

Coursework web app with a Vue frontend and Express/SQLite backend for account registration, email verification, login, JWT authentication, and basic security testing.

## Screenshot

![Login page](docs/screenshots/home.jpg)

## Tech Stack

- Vue 3, Vite, Pinia, TailwindCSS
- Express, SQLite, bcrypt, JWT
- Resend email API for verification codes

## Run Locally

Frontend:

```bash
npm install
npm run dev
```

Backend:

```bash
cd server
npm install
cp .env.example .env
npm run dev
```

## Configuration

Set `JWT_SECRET` in `server/.env`. Add `RESEND_API_KEY` only if email delivery is needed.

## Docs

- `BUG_MANUAL.md`: bug and security test notes
- `TEST_RESULTS.md`: test summary
