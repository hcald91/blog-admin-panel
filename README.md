# Blog Admin Panel

A lightweight blog admin panel where you can write a post, attach an image, and publish it instantly. Posts are stored in Firebase Realtime Database and images in Firebase Storage, so new posts appear live without a page reload.

Project #2 of my [50 Front-end Projects](https://github.com/hcald91?tab=repositories) series.

## Live preview

[https://hcald91.github.io/blog-admin-panel/](https://hcald91.github.io/blog-admin-panel/) *(GitHub Pages, may take 1-2 min to build after publish)*

Or clone and serve locally:

```bash
npx serve .
```

## Tech stack

- Firebase JS SDK 7.14.2 (Realtime Database, Storage, Analytics)
- Bootstrap 4.0.0
- jQuery 3.2.1 (slim)
- Popper.js 1.12.9
- Vanilla JavaScript

## What I changed in this fork

- Added meaningful `<title>`, meta description, keywords, and Open Graph tags
- Added basic client-side validation feedback on the post form (blocks empty submissions with an inline message)
- Added an `alt` attribute to the dynamically rendered post image
- Added `.gitignore`

## Credits

- Original scaffold: Sudeep

## License

MIT
