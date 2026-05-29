# Jonas Jiang Visual Journal

A minimalist photo journal website for **jonasjiang.com**.

## Tech Stack

- Vite
- React
- Plain CSS
- Framer Motion
- Lucide React
- Netlify-ready configuration

## Local Development

```bash
npm install
npm run dev
```

## Production Build

```bash
npm run build
```

## Deploy on Netlify via GitHub

1. Create a new GitHub repository, for example: `jonasjiang-photo-journal`.
2. Upload or push this project into the repository.
3. In Netlify, choose **Add new site > Import an existing project**.
4. Connect GitHub and select the repository.
5. Netlify should auto-detect:
   - Build command: `npm run build`
   - Publish directory: `dist`
6. After deployment, add the custom domain:
   - `jonasjiang.com`
   - optionally also `www.jonasjiang.com`

## Replace Images

Put real photos into:

```text
public/images/
```

Then update image paths inside:

```text
src/data/stories.js
src/data/gallery.js
```

Example:

```js
cover: "/images/new-zealand-road.jpg"
```

## Suggested Content Flow

Start with 5 photo stories:

1. South Island Road Notes
2. Tokyo, Between Stations
3. Shanghai After Work
4. Courtside Afternoons
5. Dunedin Light

Keep each story concise: 8–20 images, short captions, one closing note.
