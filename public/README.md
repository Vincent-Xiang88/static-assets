
# MP3 Folder - Vercel Static Hosting

This folder contains publicly accessible MP3 files hosted on Vercel.

## 📂 Access Files

Once deployed, you can access files like this:

```
https://your-vercel-project.vercel.app/music/y1424.mp3
```

## 📝 Update File List

To provide a browsable file list at `/music/`, edit `public/music/index.html` manually.

### How to update:

1. Go to GitHub repository → `public/music/index.html`
2. Add new `<li>` entries inside the `<ul>` tag like:

```html
<li><a href="new-file.mp3">new-file.mp3</a></li>
```

3. Commit changes to trigger re-deploy.

---

This lets users visit: `https://your-vercel-project.vercel.app/music/` and see a list of files.
