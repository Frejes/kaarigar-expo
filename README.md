# Kaarigar Expo – Mela Registration Platform

A responsive, mobile-app-style web app (HTML + vanilla JS, no build step) for Admins, Kaarigars (artisans) and Visitors.

## Run in VS Code
1. File > Open Folder... and choose `kaarigar-expo`.
2. Install the recommended extension "Live Server" when prompted.
3. Right-click `index.html` > "Open with Live Server".
   Or in the terminal: `npm start` and open http://localhost:3000

Demo logins: admin `admin@kaarigar.expo` / `admin123`; kaarigar `meera@demo.in` / `demo`.

## Built
- **Admin:** create melas (name, date, location, description); approve/reject kaarigar applications; see visitors who RSVP'd per event.
- **Kaarigar:** sign up, craft profile (craft type, description, optional photo, auto-resized), apply to melas, see pending/approved/rejected.
- **Visitor:** sign up, browse upcoming melas, RSVP, see approved kaarigars on each event page.
- Basic email/password login with role-based dashboards.
- Responsive, app-style UI: bottom tab bar on phones, light/dark theme, safe-area support, Add-to-Home-Screen meta tags.
- SEO basics: semantic HTML, per-page title and meta description, Open Graph tags, schema.org `Event` JSON-LD.

- **Backend & Database:** Integrated live **Supabase PostgreSQL** cloud backend with real-time sync across devices, plus automatic fallback to browser `localStorage` when offline.
