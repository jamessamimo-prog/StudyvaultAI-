# StudyVault

Digital bookstore + learning platform (static frontend + Vercel API).

## Deploy (GitHub → Vercel)

1. Create a GitHub repo
2. Upload **all files at the repo root** (not inside a subfolder):
   - `index.html`
   - `vercel.json`
   - `api/gemini.js`
   - `README.md`
3. On Vercel: **Import Git Repository** (do not use only "upload files" if you need the API)
4. Add **one** Environment Variable:
   - Name: `GEMINI_API_KEY`
   - Value: your key from https://aistudio.google.com/apikey
5. Deploy

## Admin

- Email: `adminpresident@gmail.com`
- Password: `LOB419LOB419`

## Notes

- No Vite. No local `npm install` required.
- AI calls go to `/api/gemini` (server uses `GEMINI_API_KEY`).
- Purchases and users are stored in the browser LocalStorage (demo commerce).
