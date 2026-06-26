# Escaping the Australian Outback

A single-page HTML canvas game that can be deployed directly to Vercel as a static site.

## Play locally

Open `index.html` in a browser, or serve the folder with any static file server:

```bash
python3 -m http.server 3000
```

Then visit <http://localhost:3000>.

## Deploy to Vercel

1. Import this repository in Vercel.
2. Leave the framework preset as **Other**.
3. Use the repository root as the output/static directory.
4. Deploy.

`vercel.json` rewrites all routes to `index.html`, so the game loads from the root URL and from refreshed paths.
