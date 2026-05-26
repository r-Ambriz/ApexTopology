# Deployment Notes

## GitHub

1. Create a new repository.
2. Upload or commit the contents of this folder.
3. Keep `index.html` at the repository root.

## Vercel

1. Import the GitHub repository in Vercel.
2. Use the default static project settings.
3. Build command can stay empty or use:

```bash
npm run build
```

4. Output directory can stay empty because the app is served from the project root.

## Important

The app currently calls Anthropic directly from the browser. For production use, move that API call behind a serverless API route so API keys are not exposed in client-side code.
