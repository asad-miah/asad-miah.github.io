# Updating asad-miah.github.io

Copy these into the root of your repo, overwriting existing files:

- `hugo.yaml` – disables Hugo's generated homepage so the new one is served
- `static/index.html` – the new single-page portfolio
- `static/css/organic.css` – its stylesheet
- `static/cv/Asad-Miah-CV.pdf` – the CV behind every "Download CV" button

`static/images/portrait.png` is unchanged and already in the repo.

Then commit and push to `main`. Your existing GitHub Actions workflow (`.github/workflows/hugo.yml`) builds and deploys it.

```
git add hugo.yaml static/
git commit -m "Redesign portfolio homepage"
git push
```

Optional clean-up: the old pages in `content/` (about, experience, projects, …) still build at their old URLs. They're no longer linked from the homepage, so you can delete them. If you do, add `"page", "section"` to `disableKinds` as well.
