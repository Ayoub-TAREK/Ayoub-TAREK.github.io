# ayoub-website

Personal academic site: plain HTML/CSS with a little vanilla JS, hosted on GitHub Pages.
Layout inspired by [ahmedloug.github.io](https://ahmedloug.github.io/) and [al-folio](https://github.com/alshedivat/al-folio).

## Structure

```
index.html          About, experience, awards, News table, contact icons
projects.html       Project cards
404.html            Not-found page (GitHub Pages serves it automatically)
assets/css/style.css
assets/js/main.js   Theme toggle, mobile menu, footer year
images/profile.jpg  Profile photo (same as GitHub avatar)
images/projects/    Project thumbnails
images/cv.pdf       Your CV (add it)
.nojekyll           Tells GitHub Pages to serve files as-is
```

## Preview locally

```
python -m http.server 8000
```
then open http://localhost:8000.

## Deploy

1. Create a public repo named `<your-username>.github.io`.
2. Push this folder to the `main` branch.
3. Repo **Settings → Pages**: Source = "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site goes live at `https://<your-username>.github.io/` within a minute or two.

## TODO checklist

Search the project for `TODO` to find each spot. Visible ones are yellow-highlighted `<span class="todo">` elements; delete the span once you've filled it in.

- [ ] `images/cv.pdf`: add your CV
- [ ] Social links in `index.html` (email, LinkedIn, Google Scholar)
- [ ] Internship start month (callout in `index.html`)
- [ ] Excelya description and exact dates
- [ ] Surgical JEPA result
- [ ] Spotify ML card in `projects.html` (currently only on the About page)
- [ ] Rewrite the second bio paragraph in your own voice
- [ ] Check the location under the photo
