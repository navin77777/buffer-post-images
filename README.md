# Instagram Post Images

Public media repository for the `relax.ai.app` Buffer scheduler.

## Contents

- `posts/` contains 10 carousel posts.
- Every carousel contains five `1080 × 1350` JPEG slides.
- `posts.json` contains titles, captions, hashtags, and slide text.

## Connect this folder to GitHub

Create an empty **public** GitHub repository, then run:

```powershell
cd E:\buffer-post-images
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
git branch -M main
git add .
git commit -m "Add Instagram carousel images"
git push -u origin main
```

If GitHub asks you to authenticate, use GitHub Desktop, the GitHub CLI, or
your normal Git credential manager. Do not store a GitHub token in this
repository.

## Public image URL format

After pushing, an image URL will look like:

```text
https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPOSITORY/main/posts/meditation-changes-your-day/01.jpg
```

Keep this repository public and do not delete or rename images until Buffer
has published every scheduled post.

## Security

This repository intentionally contains no Buffer API key, GitHub token,
Cloudinary credential, or `.env` file.
