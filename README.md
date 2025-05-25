
# Static Assets for jsDelivr Demo

This repository contains example static files for use via [jsDelivr CDN](https://www.jsdelivr.com/).

## 📁 Folder Structure

```
css/
  └── main.css        ← Sample CSS stylesheet

js/
  └── app.js          ← Sample JavaScript file

images/
  └── logo.svg        ← Sample SVG icon
```

## 🚀 Usage via jsDelivr

You can reference these files directly in your HTML using jsDelivr CDN:

```html
<!-- CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/yourusername/static-assets/css/main.css">

<!-- JavaScript -->
<script src="https://cdn.jsdelivr.net/gh/yourusername/static-assets/js/app.js"></script>

<!-- SVG -->
<img src="https://cdn.jsdelivr.net/gh/yourusername/static-assets/images/logo.svg">
```

Make sure to replace `yourusername` with your actual GitHub username.

## 📝 Notes

- This repo must be **public** to work with jsDelivr.
- jsDelivr caches files, so use versioning or commit hashes if files change frequently.
