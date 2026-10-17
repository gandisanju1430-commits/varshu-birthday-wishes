# Bestie's Birthday Surprise

A personalized birthday celebration with wishes, memory photos, a cake surprise, and WhatsApp gift choices.

## Run locally

1. Install Node.js.
2. Run `npm install`.
3. Run `npm start`.
4. Open `http://localhost:3001`.

The server uses the `PORT` environment variable when provided by a hosting service.

## Live website

Visit [Varshu's birthday surprise](https://gandisanju1430-commits.github.io/varshu-birthday-wishes/).

## Deploy on GitHub Pages

Create a GitHub repository for this project and push the project files to its `main` branch. The included GitHub Actions workflow publishes the `public/` folder. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**. After the workflow finishes, share the public URL shown in its deployment environment. The birthday page and its photos are static and do not need the Node server to run on GitHub Pages.

## Personalization

- Replace the photos and video in `public/memories/`, the gift images in `public/gifts/`, and `public/cake-surprise.jpg` with the images you want to share.
- Gift choices open WhatsApp with a prefilled message. The selected gift image downloads separately and must be attached manually in WhatsApp.
- The “My Lovely Cutiepie” page uses the four portrait photos in `public/memories/cutiepie-1.jpg` through `cutiepie-4.jpg`; the memories gallery also includes the other photos and video.
- The cinematic ending uses `public/ending-photo.png` as its background image.
- After the birthday-date gate, drag the bow onto the heart to reveal the birthday celebration; keyboard users can focus the bow and aim with the arrow keys.
