
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

---

## 🧾 4. `docs/README.md`

```markdown
# Jobbridge – dokumentation

I `docs/` samlar vi all icke-kod som är viktig för projektet.

Föreslagna filer:

- `vision.md`  
  Beskriver varför Jobbridge finns, vilken förändring vi vill skapa på
  arbetsmarknaden och hur vi skiljer oss från andra.

- `product-spec.md`  
  Beskriver MVP-scope, user stories, skärmar/flöden och framtida features.

- `tech-architecture.md`  
  Översikt över frontend/backend, databaser, AI-integration och hur saker
  hänger ihop.

- `roadmap.md`  
  Grov tidslinje: vad vi vill bygga de närmaste månaderna och i vilken ordning.

Dokumentationen är minst lika viktig som koden – den håller oss synkade
som team och gör det lättare att ta in fler personer i projektet.

