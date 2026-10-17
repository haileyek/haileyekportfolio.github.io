# Hailey Ek — Creative Portfolio (Version 3)

## Publish to GitHub Pages
1. Unzip this folder.
2. In your `haileyek.github.io` GitHub repository, upload the **contents** of this folder (not the outer folder): `index.html`, `style.css`, `script.js`, `photos.js`, `projects.js`, and the `images` folder.
3. Commit changes. In Settings → Pages, choose Deploy from a branch → main → /(root) if it is not already configured.
4. Your website should appear at `https://haileyek.github.io/` after deployment.

## Add photos
1. Place a new photo in the `images` folder (e.g., `photo-41.jpg`). Resize for web when possible, usually 1600–2200 px on the long edge.
2. Open `photos.js`. Copy an existing photo object and edit `src`, `title`, `category`, and `alt`.
3. Use one of these exact categories: `People & Connection`, `Faith & Culture`, `Places & Details`.
4. Upload the updated `photos.js` and new image to GitHub. All galleries and collection counts update automatically.
5. To change a collection cover, edit the `cover` value in `script.js` under `categories`.

## Add videos or Reels
1. Open `projects.js` and add entries to `window.CONTENT_PROJECTS`.
2. Use `video: "videos/example.mp4"` for a video file you upload (create a `videos` folder), or `url: "https://..."` for a public video link.
3. Use `poster: "images/cover.jpg"` for a thumbnail, and fill in `title`, `type`, and `description`.
4. The Coming Soon block disappears automatically once a project is added. Large video files are better hosted on an external video platform.

## Before applying
- Add a real email/contact link in `index.html` (contact section).
- Check photo permissions, especially recognizable children and participants in religious ceremonies.
- Review image titles and About text for accuracy.
- Test the website on a phone and desktop.

No frameworks, build tools, or paid hosting are required.

## Latest update
Added 20 new photographs (photo-21.jpg through photo-40.jpg), organized into the existing three collections. The portfolio now includes 40 photographs.

## Contact links
The contact section includes hailey.ek@icloud.com and Instagram @haileymaeek. To update either, edit the footer links in `index.html`.


## Updated collections
The homepage displays four clickable collections; full photo galleries open only after selecting a collection.
