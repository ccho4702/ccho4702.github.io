# Changho Choi — academic website

This is Changho Choi's research homepage, built with the [al-folio](https://github.com/alshedivat/al-folio) academic website template. It is configured for the GitHub Pages address **https://ccho4702.github.io**.

## What is on the site

- Introduction, research interests, email, Google Scholar, and GitHub links: `_pages/about.md`
- Publications: `_bibliography/papers.bib` and `_pages/publications.md`
- Undergraduate transcript link: `_pages/transcripts.md`, with the PDF in `assets/pdf/`
- Site identity and layout settings: `_config.yml`
- Social links: `_data/socials.yml`
- Temporary initials artwork: `assets/img/changho-avatar.svg`

The site is in English for an international academic audience. The avatar is a placeholder; replace it with a portrait and update the `profile.image` field in `_pages/about.md` if desired. No CV has been included because no CV file was supplied.

## Preview locally

With a current Ruby and Bundler installation:

```sh
bundle install
bundle exec jekyll serve
```

Open http://127.0.0.1:4000. A production build is made with `bundle exec jekyll build`.

## Updating the published site

The homepage is live at **https://ccho4702.github.io**. Edit these source files and push a commit to `main`. The included **Deploy site** workflow builds the site and publishes it from the `gh-pages` branch.

The undergraduate transcript PDF in `assets/pdf/` is publicly downloadable. No graduate transcript is included.

The source site remains under the [al-folio license](LICENSE).
