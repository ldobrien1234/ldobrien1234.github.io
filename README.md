# liamwebsite

Source for Liam D. O'Brien's personal website: a static site (plain HTML and CSS, no build step).

## Structure

```
index.html        About page (professional + personal)
projects.html     Research, publications, expository papers, code
contact.html      Contact links
assets/style.css  Shared stylesheet
assets/img/       Photos and figures
assets/files/     PDFs
```

## Preview locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy on GitHub Pages

1. Create a repository named `ldobrien1234.github.io` on GitHub (public).
2. Point this folder at it and push:
   ```
   git remote set-url origin https://github.com/ldobrien1234/ldobrien1234.github.io.git
   git push -u origin main
   ```
3. On GitHub: Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
4. The site will be live at https://ldobrien1234.github.io within a minute or two.

To edit content, change the HTML files directly and push again.
