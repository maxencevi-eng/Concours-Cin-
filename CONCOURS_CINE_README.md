Concours Ciné extension

This workspace was extended with a "Concours Ciné" feature.

New pages/components added under `src/components`:

- `navbar` — top navigation to access Concours Ciné, Classement, Profil, Admin
- `concours-cine` — main contest page showing weekly photos, timer, answer input
- `leaderboard` — ranking page
- `profile` — user profile page
- `admin` — admin landing page

State for contests, users and submissions is persisted to localStorage with keys: `contests`, `cine_users`, `cine_submissions`, `cine_current_contest`.

To test locally: run the usual dev server (e.g. `npm install` then `npm run dev`) and use the top navbar to navigate to "Concours Ciné".

Notes:
- The implementation is in-memory/localStorage for simplicity and demo purposes.
- Admin pages are minimal; further admin UI (create contests, upload photos) can be added next.
