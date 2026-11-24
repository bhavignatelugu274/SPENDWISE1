<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/7e9f24b6-18e5-4001-b276-4fcd4e21d873

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

## Deploy to GitHub Pages

The `main` branch automatically builds and deploys the app to GitHub Pages.
In the repository settings, set **Pages → Build and deployment → Source** to
**GitHub Actions**. The project is published at
`https://bhavignatelugu274.github.io/SPENDWISE1/`.
