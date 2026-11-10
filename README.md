# khushboo-portfolio

My personal site. One self-contained `index.html`: the styles, the scripts and my
photo are all inline, so there is no build step and nothing to install. Open the
file in a browser and it works.

Live at **https://khushbooshaurya5.github.io/khushboo-portfolio/**

## What's on it

Who I am, where I'm based, the roles I've held, the projects I've published, my
degrees and my certifications. The project cards each link to their own
repository.

## Working on it

```
git clone https://github.com/khushbooshaurya5/khushboo-portfolio
cd khushboo-portfolio
python3 -m http.server 8000
```

Then open http://localhost:8000. Edit `index.html` and reload; there is no
watch task because there is nothing to compile.

A push to `main` republishes the site through the workflow in
`.github/workflows/pages.yml`.

## A note on the three external files

The page pulls Google Fonts, the EmailJS browser client and the QRious QR-code
library from CDNs. Everything else is inline. If any of those three fail to
load the page still renders and still works, and the contact form falls back to
asking you to email me directly rather than silently failing.

## Contact

khushbooshaurya@gmail.com · [LinkedIn](https://www.linkedin.com/in/khushboo-k-5053a9b7/) · [GitHub](https://github.com/khushbooshaurya5)
