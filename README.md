# Bestie's Birthday Surprise

A personalized birthday celebration with wishes, memory photos, a cake surprise, and WhatsApp gift choices.

## Run locally

1. Install Node.js.
2. Run `npm install`.
3. Run `npm start`.
4. Open `http://localhost:3001`.

The server uses the `PORT` environment variable when provided by a hosting service.

## Deploy on GitHub Pages

Create a GitHub repository for this project and push the project files to its `main` branch. The included GitHub Actions workflow publishes the `public/` folder. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**. After the workflow finishes, share the public URL shown in its deployment environment. The birthday page and its photos are static and do not need the Node server to run on GitHub Pages.

## Personalization

- Replace the photos in `public/memories/`, `public/gifts/`, and `public/cake-surprise.jpg` with the images you want to share.
- Gift choices open WhatsApp with a prefilled message. The selected gift image downloads separately and must be attached manually in WhatsApp.
- The “Three Years Apart” chapter uses the local memory photos in `public/memories/`. Add real milestone dates to its timeline in `public/index.html` when you have them; no dates are guessed.
