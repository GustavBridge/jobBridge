
---

## 🧾 3. `backend/README.md`

```markdown
# Jobbridge – backend

Det här är API- och logiklagret för Jobbridge.

## Tech-stack (planerad)

- Node.js
- TypeScript
- Express
- PostgreSQL + pgvector
- OpenAI API (GPT-4o mini + text-embedding-3-large)

## Huvudansvar

- Hantera registrering och inloggning (e-post + lösenord)
- Ta emot kandidaters och arbetsgivares svar (intervjufrågor)
- Anropa OpenAI för att generera sammanfattningar ("profiler")
- Skapa embeddings och spara dem i databasen
- Matcha kandidater och jobb via cosine similarity
- Exponera REST-endpoints till frontend

## Centrala endpoints (MVP)

- `POST /auth/register`
- `POST /auth/login`

- `POST /candidate/answers`
- `GET  /candidate/profile/:id`

- `POST /company/answers`
- `GET  /company/profile/:id`

- `GET  /match/candidate/:id`  
- `GET  /match/company/:id`

## Utveckling

```bash
cd backend
npm install
npm run dev   # startar API i utvecklingsläge
