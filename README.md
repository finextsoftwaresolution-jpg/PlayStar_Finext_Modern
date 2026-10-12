# PlayStar Digital — Finext Modern Admin Dashboard

A responsive HTML/CSS/JavaScript front-end demo, rebuilt with a modern dark navy + electric violet/cyan visual system.

## Run it
Open `index.html` in a current browser. No build step or package installation is required.

## Demo login
- Email: `admin@playstardigital.test`
- Password: `Finext@2026`

## Included interactions
- Demo login and logout, remember-device toggle, show/hide password
- Responsive navigation drawer for mobile
- Overview dashboard, KPI cards, revenue chart range switching, platform chart
- Approve/review actions for sample pending releases
- Release filtering, global search, page navigation
- Create release draft, add artist, create support ticket, invite user (demo-only)
- Light/dark theme toggle, notifications toast, profile menu
- Session/theme persistence in browser storage

## Important production note
This is a client-side prototype. Login credentials are demo-only and validation occurs in JavaScript; browser storage is not secure authentication. There is no real database, role enforcement, payment processing, royalty calculation, or authorized music-store distribution in this package. Before production, implement a backend, hashed passwords, secure server sessions, CSRF protection, rate limiting, RBAC/permissions enforced server-side, audit trails, database migrations, and authorized distributor API integration. All shown figures and store actions are sample/demo data.
