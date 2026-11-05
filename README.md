# KL STREAM — React + Vite

A student-friendly React conversion of the original KL STREAM project.

## Run locally
1. Install Node.js (LTS).
2. Open this folder in VS Code.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL printed by Vite.

## Build
Run `npm run build`. The production files are generated in `dist`.

## Demo accounts
- Admin email: `admin@klstream.com`
- Admin password: `admin123`
- User: create an account through Sign up.

## Data
This academic demonstration uses browser Local Storage for users, current login, videos, watchlists, viewing history and creator submissions. Data stays in the same browser and device. Clearing browser storage removes it.

**Security note:** Local Storage authentication is only for a classroom demonstration. It is not secure for real users; a production application needs a trusted backend and secure password authentication. Do not use a real password here.

## Main React concepts used
- Components and component rendering
- `useState`
- Props
- `react-router-dom` (`Routes`, `Route`, `Link`, `NavLink`, `useNavigate`, `useParams`)
- Local Storage
