# 🚀 Web Development Roadmap: 97-Day Execution Plan

## 🎯 16-Week Goal Statement
My objective is to transform into a capable full-stack developer by building **12+ real-world projects** from scratch between **Sept 26 and Dec 31, 2026**. I am committing to a disciplined daily routine to master front-end systems, backend logic, relational databases, and modern component-driven architectures.

---

## 📅 Phase Allocations & Targets

| Phase | Focus | Dates | Projects |
| :--- | :--- | :--- | :--- |
| **Phase 1** | HTML & CSS Foundations | Sept 26 – Oct 9 | Profile Card, Recipe Page, Landing Page |
| **Phase 2** | JavaScript & the DOM | Oct 10 – Oct 23 | To-Do List, Quiz App, Expense Tracker |
| **Phase 3** | APIs & Async JavaScript | Oct 24 – Nov 6 | Weather Dashboard, Movie Search, GitHub Explorer |
| **Phase 4** | Backend Foundations | Nov 7 – Nov 20 | Quotes API, Notes API + Frontend |
| **Phase 5** | Databases & Auth | Nov 21 – Dec 4 | Blog Platform + DB, Blog Authentication |
| **Phase 6** | Modern Frontend (React) | Dec 5 – Dec 18 | React To-Do Rebuild, Full-Stack Task Manager |
| **Phase 7** | Capstone Production | Dec 19 – Dec 31 | "Collabo" Real-Time Project Board |

---

## 🛠️ Detailed Daily Log

### 🟦 PHASE 1: HTML & CSS Foundations (Sept 26 – Oct 9)
#### Project 1.1 — Personal Profile Card
- [x] **Day 1 (Sept 26):** Set up project folder + git repo; write semantic HTML skeleton (`<header>`, `<main>`, `<section>`, `<footer>`) with placeholder content.
- [x] **Day 2 (Sept 27):** Style the card using the box model + Flexbox centering; swap in real content (photo, bio, links).
- [ ] **Day 3 (Sept 28):** Add responsive breakpoints, CSS variables for theming, and hover states; test at mobile widths.
- [ ] **Day 4 (Sept 29) — Buffer/Review:** Attempt dark/light mode stretch goal, clean up CSS, push to GitHub with a README, verify on 2+ screen sizes.

#### Project 1.2 — Recipe Page
- [ ] **Day 5 (Sept 30):** Plan content structure; build semantic HTML (ingredients list, numbered steps, image + figcaption).
- [ ] **Day 6 (Oct 1):** Implement CSS Grid layout for desktop; establish a typography hierarchy.
- [ ] **Day 7 (Oct 2):** Add mobile-first media queries; test how the layout collapses on small screens.
- [ ] **Day 8 (Oct 3) — Buffer/Review:** Attempt the print-stylesheet stretch goal, fix layout bugs, push to GitHub with README.

#### Project 1.3 — Multi-Section Landing Page
- [ ] **Day 9 (Oct 4):** Wireframe sections (nav, hero, features, pricing, footer); scaffold the HTML.
- [ ] **Day 10 (Oct 5):** Build the CSS Grid page layout + hero section styling.
- [ ] **Day 11 (Oct 6):** Build a responsive nav (hamburger via the CSS checkbox trick) + features grid.
- [ ] **Day 12 (Oct 7):** Style pricing cards and footer; add sticky nav + CSS transitions; test responsiveness end-to-end.
- [ ] **Day 13 (Oct 8) — Edge Cases/Stretch:** Add scroll-triggered fade-in animations, cross-browser check, fix any layout breaks.

#### 🔄 Catch-Up Buffer
- [ ] **Day 14 (Oct 9):** Full phase review — revisit all three projects, fix lingering bugs, finalize all READMEs, confirm every repo is pushed before starting JavaScript.

---

### 🟨 PHASE 2: JavaScript Fundamentals & the DOM (Oct 10 – Oct 23)
#### Project 2.1 — Interactive To-Do List
- [ ] **Day 15 (Oct 10):** Plan your state shape (array of task objects); scaffold HTML + link your JS file.
- [ ] **Day 16 (Oct 11):** Implement adding tasks via DOM creation (`createElement`, `appendChild`) + event listeners.
- [ ] **Day 17 (Oct 12):** Implement complete/delete using event delegation (one listener on the parent, not one per item).
- [ ] **Day 18 (Oct 13):** Add filtering (all/active/done) + `localStorage` persistence (save/load with JSON).
- [ ] **Day 19 (Oct 14) — Buffer/Review:** Attempt drag-and-drop reordering stretch, test that data survives a refresh, push to GitHub.

#### Project 2.2 — Timed Quiz App
- [ ] **Day 20 (Oct 15):** Model your question data (array of objects); scaffold the “state object + render function” pattern.
- [ ] **Day 21 (Oct 16):** Build the question flow — show question, capture answer, advance — plus score tracking.
- [ ] **Day 22 (Oct 17):** Add a countdown timer (`setInterval` / `clearInterval`) + a results screen.
- [ ] **Day 23 (Oct 18) — Buffer/Review:** Add question-shuffling stretch, fix timer edge cases, push to GitHub.

#### Project 2.3 — Personal Expense Tracker
- [ ] **Day 24 (Oct 19):** Plan the data model (income/expense objects with category); build the form + basic validation.
- [ ] **Day 25 (Oct 20):** Render a dynamic list from the array; implement add/delete (CRUD pattern).
- [ ] **Day 26 (Oct 21):** Calculate running balance + category totals using `reduce()`.
- [ ] **Day 27 (Oct 22):** Add `localStorage` persistence; handle edge cases (empty states, negative numbers).
- [ ] **Day 28 (Oct 23) — Buffer/Review:** Attempt a CSS-only bar chart stretch goal, clean up code, push to GitHub.

---

### 🟩 PHASE 3: APIs & Asynchronous JavaScript (Oct 24 – Nov 6)
#### Project 3.1 — Weather Dashboard
- [ ] **Day 29 (Oct 24):** Get a free weather API key; read the docs; scaffold the search UI.
- [ ] **Day 30 (Oct 25):** Implement `fetch()` + `async / await` to pull current weather for a searched city.
- [ ] **Day 31 (Oct 26):** Add error handling (invalid city, failed request) and a loading state.
- [ ] **Day 32 (Oct 27) — Buffer/Review:** Geolocation auto-detect + unit toggle stretch, push to GitHub safely.

#### Project 3.2 — Movie/Show Search App
- [ ] **Day 33 (Oct 28):** Read the movie API docs; scaffold the search UI + a basic working fetch.
- [ ] **Day 34 (Oct 29):** Implement debounced search input; render a results grid with posters.
- [ ] **Day 35 (Oct 30):** Build a movie detail view + proper loading/error/empty states.
- [ ] **Day 36 (Oct 31):** Implement “favorites” via `localStorage`; add pagination or “load more.”
- [ ] **Day 37 (Nov 1) — Buffer/Review:** Attempt hash-based routing stretch, push to GitHub.

#### Project 3.3 — GitHub Profile/Repo Explorer
- [ ] **Day 38 (Nov 2):** Scaffold the search UI; fetch and render a GitHub user’s profile info.
- [ ] **Day 39 (Nov 3):** Fetch and render their repo list, practicing nested JSON parsing.
- [ ] **Day 40 (Nov 4):** Handle API errors/rate limits (403/404) gracefully in the UI.
- [ ] **Day 41 (Nov 5):** Add sort/filter by stars or language (stretch goal).
- [ ] **Day 42 (Nov 6) — Buffer/Review:** Polish all UI states, finalize READMEs for all API projects, push to GitHub.

---

### 🟧 PHASE 4: Backend Fundamentals — Node.js & Express (Nov 7 – Nov 20)
#### Project 4.1 — REST API for a “Quotes” Service
- [ ] **Day 43 (Nov 7):** Learn the request/response cycle; initialize a Node project + basic Express server.
- [ ] **Day 44 (Nov 8):** Build `GET /quotes` and `GET /quotes/:id` using an in-memory array or JSON file.
- [ ] **Day 45 (Nov 9):** Build `POST /quotes` + `express.json()` middleware; test with Postman/curl.
- [ ] **Day 46 (Nov 10):** Build `DELETE /quotes/:id` and `PUT / PATCH` for updates.
- [ ] **Day 47 (Nov 11):** Add input validation middleware; handle bad requests (400s) and not-found (404s).
- [ ] **Day 48 (Nov 12):** Stretch — add pagination query params; refactor routes into separate files.
- [ ] **Day 49 (Nov 13) — Buffer/Review:** Test every endpoint methodically, write API docs in README, push to GitHub.

#### Project 4.2 — Notes API + Vanilla JS Frontend
- [ ] **Day 50 (Nov 14):** Scaffold a fresh Notes API using the same CRUD pattern as 4.1.
- [ ] **Day 51 (Nov 15):** Configure CORS; build all CRUD endpoints; test fully with Postman.
- [ ] **Day 52 (Nov 16):** Build a vanilla JS frontend that fetches and displays notes from your live API.
- [ ] **Day 53 (Nov 17):** Wire up create/delete from the frontend to the backend.
- [ ] **Day 54 (Nov 18):** Wire up edit/update; add `.env` config for local dev; handle UI network errors.
- [ ] **Day 55 (Nov 19):** Stretch — add file upload for attachments (`multer`) or a search endpoint.
- [ ] **Day 56 (Nov 20) — Buffer/Review:** Full end-to-end test of frontend + backend together, push both to GitHub.

---

### 🟪 PHASE 5: Databases & Authentication (Nov 21 – Dec 4)
#### Project 5.1 — Blog Platform, Backend + Database
- [ ] **Day 57 (Nov 21):** Choose PostgreSQL or MongoDB; design schema relationships on paper.
- [ ] **Day 58 (Nov 22):** Set up the database (local or hosted); connect Express to it.
- [ ] **Day 59 (Nov 23):** Build CRUD endpoints for posts against the real database.
- [ ] **Day 60 (Nov 24):** Build CRUD endpoints for comments, linked to posts (one-to-many).
- [ ] **Day 61 (Nov 25):** Add seed data + migrations; test all endpoints with Postman.
- [ ] **Day 62 (Nov 26):** Stretch — full-text search on posts, or tags/categories (many-to-many).
- [ ] **Day 63 (Nov 27) — Buffer/Review:** Verify data integrity, document the schema in README, push to GitHub.

#### Project 5.2 — Add Authentication to the Blog
- [ ] **Day 64 (Nov 28):** Implement password hashing using `bcrypt` on the register endpoint.
- [ ] **Day 65 (Nov 29):** Build the login endpoint; implement sessions or JWTs.
- [ ] **Day 66 (Nov 30):** Build auth middleware to protect routes; test with valid/invalid tokens.
- [ ] **Day 67 (Dec 1):** Enforce authorization — users can only edit/delete their own posts.
- [ ] **Day 68 (Dec 2):** Handle auth edge cases: expired tokens, wrong password, duplicate emails.
- [ ] **Day 69 (Dec 3):** Stretch — password reset flow via email or role-based access controls.
- [ ] **Day 70 (Dec 4) — Buffer/Review:** Full auth flow test, push to GitHub.

---

### 🟥 PHASE 6: Modern Frontend — React & Full-Stack Integration (Dec 5 – Dec 18)
#### Project 6.1 — Rebuild the To-Do List in React
- [ ] **Day 71 (Dec 5):** Scaffold a React project; convert your static markup into a component structure.
- [ ] **Day 72 (Dec 6):** Implement `useState` for the task list + a controlled form input.
- [ ] **Day 73 (Dec 7):** Implement complete/delete via props/callbacks; add proper `key` properties.
- [ ] **Day 74 (Dec 8):** Extract reusable components (`TaskItem`, `TaskForm`); add filtering options.
- [ ] **Day 75 (Dec 9) — Buffer/Review:** Try the `useReducer` stretch goal, push to GitHub.

#### Project 6.2 — Full-Stack Task Manager (React + Express + DB)
- [ ] **Day 76 (Dec 10):** Design data model (tasks scoped per user); scaffold backend + frontend structures.
- [ ] **Day 77 (Dec 11):** Adapt Phase 5 auth into this backend; test register/login endpoints.
- [ ] **Day 78 (Dec 12):** Build full CRUD task endpoints scoped to the logged-in user.
- [ ] **Day 79 (Dec 13):** Build React auth UI + store authentication state via Context API.
- [ ] **Day 80 (Dec 14):** Connect React to the backend — fetch and display the logged-in user’s tasks.
- [ ] **Day 81 (Dec 15):** Wire up create/update/delete from React to the API; add redirects.
- [ ] **Day 82 (Dec 16):** Handle loading/error states throughout code; fix session edge cases.
- [ ] **Day 83 (Dec 17):** Stretch — WebSockets for live updates, or a drag-and-drop Kanban board.
- [ ] **Day 84 (Dec 18) — Buffer/Review:** Deploy frontend (Vercel) + backend (Render) + DB; push to GitHub.

---

### 👑 PHASE 7: CAPSTONE — "Collabo," Real-Time Project Board (Dec 19 – Dec 31)
#### Design & API (Days 85–87)
- [ ] **Day 85 (Dec 19):** Design data models (Users ➔ Workspaces ➔ Columns ➔ Cards) on paper first.
- [ ] **Day 86 (Dec 20):** Scaffold backend; build board/column CRUD endpoints; apply security auth middleware.
- [ ] **Day 87 (Dec 21):** Build card CRUD endpoints; test completely via Postman.

#### React Frontend (Days 88–92)
- [ ] **Day 88 (Dec 22):** Scaffold the React app; build board lists + login/register views.
- [ ] **Day 89 (Dec 23):** Build the single-board view, rendering columns and cards dynamically from the API.
- [ ] **Day 90 (Dec 24):** Wire up create/edit/delete for boards, columns, and cards end-to-end.
- [ ] **Day 91 (Dec 25):** *Light day* — polish existing CRUD flows, fix any bugs found so far.
- [ ] **Day 92 (Dec 26):** Ensure plain CRUD is completely stable before adding complex libraries.

#### Advanced Sync & Polish (Days 93–97)
- [ ] **Day 93 (Dec 27):** Add drag-and-drop mechanics of cards between columns using an external library.
- [ ] **Day 94 (Dec 28):** Implement real-time sync via WebSockets so multiple open tabs see live changes.
- [ ] **Day 95 (Dec 29):** Handle failure edge cases — empty states, failed requests, unauthorized access.
- [ ] **Day 96 (Dec 30):** Final UI styling polish pass, cross-browser validation, and device responsiveness check.
- [ ] **Day 97 (Dec 31):** Deploy everything live, write a complete case-study README, and showcase!

---

## 🛡️ Daily Execution Strategy: Rules of the Road
1. **Build Before Research:** Try the day's task using what you already know for 20–30 minutes before looking up anything. The productive struggle is where true learning occurs.
2. **Search Concepts, Not Snippets:** Search "how does event delegation work", never copy-paste specific layout syntax from random bug threads.
3. **Primary References First:** Rely strictly on official documentation (MDN, React Docs, Express Docs) over tutorial video workflows. 
4. **Isolate and Debug:** Read error logs line-by-line. Comment out breaking elements systematically and check values using variables instead of guessing blindly.
5. **Never Paste and Move On:** If any outside snippet is utilized, re-type it manually and write inline comments explaining what each command executes.
