# AffordMed URL Shortener

A frontend-only React + Vite + TailwindCSS URL shortener with temporary links stored in `localStorage`, click tracking, and a statistics page.

## Run locally

```bash
npm install
npm run dev
```

Open the shown URL (default http://localhost:5173).

## Build

```bash
npm run build
npm run preview
```

## Notes

- Links expire 30 minutes after creation by default.
- Events (`URL_SHORTENED`, `URL_CLICKED`) are logged to `sessionStorage`.
