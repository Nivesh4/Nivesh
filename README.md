# Sportify League Management System

A responsive front-end-only sports league management website built with React JS, React Router, HTML, CSS, JavaScript and Bootstrap 5.

## Features
- Dashboard with league statistics and upcoming fixtures
- Teams: search, add and remove teams
- Players: register, search and remove players
- Matches: schedule and delete fixtures
- Standings: points table sorted by points and wins
- Responsive sidebar navigation
- Browser localStorage keeps demo changes after refresh
- No backend or database required

## Run in VS Code
1. Install **Node.js LTS** from https://nodejs.org/
2. Extract this ZIP folder.
3. Open the extracted `sport-league-management-system` folder in VS Code.
4. Open **Terminal → New Terminal**.
5. Run:

   ```bash
   npm install
   npm run dev
   ```

6. Open the local URL shown in the terminal (usually http://localhost:5173).

## Build for production
```bash
npm run build
npm run preview
```

## Project structure
```text
sport-league-management-system/
├── index.html
├── package.json
├── README.md
└── src/
    ├── main.jsx
    ├── App.jsx
    └── styles.css
```

**Note:** This is a front-end academic demo. Team, player and match changes are stored in the browser's localStorage only. No server/database is connected.
