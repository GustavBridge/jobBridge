# Jobbridge – frontend

Det här är webbklienten för Jobbridge.

## Tech-stack (planerad)

- React
- TypeScript
- Vite (eller Create React App – beroende på första setup)
- Tailwind CSS för styling
- Fetch/axios mot backend-API

## MVP-sidor

- **LandingPage**
  - Kort pitch av tjänsten
  - Val: "Jag är kandidat" / "Jag är arbetsgivare"

- **Kandidatflöde**
  - `CandidateStart` – enkel introduktion + skapa konto / logga in
  - `CandidateQuestions` – formulär med 5–7 frågor
  - `CandidateProfile` – visar AI-sammanfattad profil och matchade jobb

- **Företagsflöde**
  - `CompanyStart` – skapa konto / logga in
  - `CompanyQuestions` – 4–6 frågor om behov, roll, kultur
  - `CompanyProfile` – visar AI-genererad jobbprofil och matchade kandidater

## Utveckling

Typiskt dev-flöde (kan justeras när projektet är igång):

```bash
cd frontend
npm install
npm run dev   # kör i utvecklingsläge
