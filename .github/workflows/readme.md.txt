# GitHub Workflows

I den här mappen hamnar GitHub Actions-workflows för t.ex.:

- lint / test vid `push`
- bygg/stage-deploy av frontend
- bygg/deploy av backend

Just nu är mappen mest en placeholder tills vi lägger till vår första
`ci.yml` eller motsvarande.

Exempel på framtida filer:

- `ci.yml` – kör tester och linters automatiskt
- `deploy-frontend.yml` – deploy till Vercel/Netlify
- `deploy-backend.yml` – deploy till vald hostingplattform
