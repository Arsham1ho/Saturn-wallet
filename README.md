# Saturn Wallet

Source for the Saturn Wallet front end, distributed in this repository as a
single archive, `saturn.zip`.

## Contents of the archive

A Vite + React + TypeScript application:

- `src/App.tsx` — the main application
- `src/main.tsx`, `index.html` — entry points
- `src/index.css` — styles
- `vite.config.ts`, `package.json`, `.npmrc` — build configuration
- `README.md` — the archive's own notes
- Extensive design and setup notes under `src/*.md`, covering Alchemy RPC setup,
  balance debugging, biometric authentication, chat and user profiles, API
  architecture and API keys. Several are written in Farsi.

## Getting started

```bash
unzip saturn.zip -d saturn
cd saturn
npm install
npm run dev
```

Check `package.json` inside the archive for the exact script names, and the
`src/API_KEYS_SETUP.md` / `src/ALCHEMY_SETUP.md` notes for the RPC and API keys
the app expects.

## Note

Because the project is stored as a zip, git cannot diff or merge changes to the
source. Unpacking the archive and committing the files directly would make the
history useful again.
