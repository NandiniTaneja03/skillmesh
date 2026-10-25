# SkillMesh — Frontend Demo

A responsive HTML, CSS, and JavaScript prototype for an AI-based team formation platform.

## Run it
1. Extract `skillmesh.zip`.
2. Open the `skillmesh` folder in VS Code.
3. Open `index.html` in your browser. Recommended: use the VS Code Live Server extension.

No build tools or package installation are required. Google Fonts are loaded online; the interface otherwise runs locally.

## Working in this demo
- Responsive dashboard and navigation
- Discover talent search and role/interest filters
- Local team-match scoring based on profile skills, interests, and availability
- Editable profile saved in `localStorage`
- Create teams and add teammates
- Local chat threads saved in `localStorage`
- Availability day selection and preferred hours
- Skill overview and portfolio preview/copy
- Toast messages, modal forms, and mobile navigation

## Important demo limitations
- Profiles are sample data; they are not real users.
- Matching is a transparent JavaScript scoring heuristic, not a trained AI model.
- Browser localStorage is device/browser-specific. There is no shared database or authentication.
- Chat is local demo chat; other users do not receive messages.
- Video rooms, real GitHub integration, notifications across devices, and secure multi-user accounts need a backend and external integrations.

## Suggested next phase
Build a Spring Boot or Node.js API, PostgreSQL database, authentication, profile CRUD, team membership endpoints, and WebSocket-based messaging. Add real GitHub OAuth and an AI embedding/recommendation service later.
