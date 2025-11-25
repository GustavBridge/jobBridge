# Jobbridge – infrastruktur

`infra/` innehåller sådant som behövs för att köra systemet i sin helhet.

Exempel på innehåll:

- `docker-compose.yml`  
  För att starta databas (PostgreSQL + pgvector) och eventuellt backend i
  containrar under utveckling.

- `database/init.sql`  
  Script för att skapa databasschema, aktivera pgvector och ev. seed-data.

- `deployment-notes.md`  
  Noteringar om hur vi deployar (t.ex. Railway, Render, Fly.io, Vercel m.m.).

Syftet med den här mappen är att hålla infrastrukturen samlad så det blir
enkelt att köra igång hela systemet på en ny dator eller server.
