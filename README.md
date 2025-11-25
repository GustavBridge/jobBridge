# Jobbridge

Jobbridge är en AI-driven plattform för rekrytering där kandidater
skapar profiler genom intervjuer och tester i stället för traditionella CV:n.
Arbetsgivare beskriver sina behov på ett liknande sätt, och en
matchningsmotor hittar de bäst passande kombinationerna.

Det här repot är ett monorepo för hela projektet:

- `frontend/` – webbklienten (React)
- `backend/` – API, databas och AI-integrationer
- `docs/` – vision, produktspecifikation, roadmap m.m.
- `infra/` – Docker, databaskonfiguration och deploy-noteringar
- `.github/` – CI/CD-workflows

## MVP-mål

Första versionen (MVP) ska klara:

- Kandidatregistrering (e-post + lösenord)
- Kandidat besvarar 5–7 frågor → AI-sammanfattad profil
- Arbetsgivare besvarar 4–6 frågor → AI-genererad jobbprofil
- Embeddings för respektive profil (pgvector)
- Enkel matchning: visa topp 3 jobb för en kandidat (och tvärtom)

När detta fungerar kan vi börja testa med riktiga användare och bygga vidare.
