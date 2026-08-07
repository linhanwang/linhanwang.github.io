# linhanwang.github.io

Personal academic homepage — plain static HTML/CSS, no build step. Layout inspired by
[jonbarron.info](https://jonbarron.info/).

## Files

```
index.html            the whole page
style.css             all styling (light + dark theme via prefers-color-scheme)
images/profile.jpg    profile photo  ← replace this placeholder
images/*.jpg          paper thumbnails (520px wide, trimmed figures)
Linhan_Wang_CV.pdf    copy of ../resume_latex/linhan-resume.pdf
dcgaussian/           NeurIPS 2024 DC-Gaussian project page
```

## Editing

**Add a paper** — copy an `<article class="paper">` block in `index.html` and drop a thumbnail
into `images/`. Newest first.

**Add news** — add an `<li>` to `<ul class="news">`.

**Update the CV** — rebuild the PDF in `../resume_latex`, then
`cp ../resume_latex/linhan-resume.pdf Linhan_Wang_CV.pdf`.

## Preview locally

```sh
python3 -m http.server 8000   # then open http://localhost:8000
```
