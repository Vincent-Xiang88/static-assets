
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

public/music/
  └── bgm.mp3        ← Sample mp3 file

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

## ✅ Commit SHA Method

Format:
```
https://cdn.jsdelivr.net/gh/<GitHub用户名>/<仓库名>@<提交SHA>/<文件路径>
```

Example:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/yourusername/static-assets@e7b1d94/css/main.css">

<script src="https://cdn.jsdelivr.net/gh/yourusername/static-assets@e7b1d94/js/app.js"></script>

<img src="https://cdn.jsdelivr.net/gh/yourusername/static-assets@e7b1d94/images/logo.svg">
```

## ✅ Tag Version Method

Format:
```
https://cdn.jsdelivr.net/gh/<GitHub用户名>/<仓库名>@<版本号>/<文件路径>
```

Example:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/yourusername/static-assets@v1.0.0/css/main.css">

<script src="https://cdn.jsdelivr.net/gh/yourusername/static-assets@v1.0.0/js/app.js"></script>

<img src="https://cdn.jsdelivr.net/gh/yourusername/static-assets@v1.0.0/images/logo.svg">
```

## 📝 Notes

- This repo must be **public** to work with jsDelivr.
- jsDelivr caches files, so use versioning or commit hashes if files change frequently.
