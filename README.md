# Bhavana N S — Portfolio

Responsive React + TypeScript + Tailwind CSS portfolio with Framer Motion animations.

## Run locally

```bash
npm install
npm run dev
```

Open the URL shown by Vite (usually http://localhost:5173).

## Production build

```bash
npm run build
npm run preview
```

Deploy the `dist` folder to Netlify, Vercel, or another static host.

## Before publishing

- Replace `your.email@example.com` in `src/App.tsx` with your real contact email.
- Add your verified LinkedIn/GitHub URLs and a resume PDF when ready.
- Confirm company/project details and numerical achievements before publishing.
- Only share employer project screenshots or code with permission.

## Resume downloads
The resume is bundled as `public/Bhavana_N_S_Resume.pdf` and is copied to the
site root during `npm run build`. Both Download Resume buttons use a Blob
download to force a PDF download instead of opening a browser preview.
If the PDF cannot be fetched, the provided OneDrive sharing link opens as a fallback.
For production hosting, deploy the entire `dist/` directory (including the PDF).
Do not open `index.html` directly as a local file; use `npm run dev`.
