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

## Publish on GitHub Pages

1. Create a public repository named `ccho4702.github.io` under the `ccho4702` GitHub account.
2. Push these source files to its `main` branch.
3. Let the included **Deploy site** GitHub Actions workflow build the site. It writes the generated site to a `gh-pages` branch.
4. In the repository's **Settings → Pages**, set the source to **Deploy from a branch**, choose `gh-pages` and `/(root)`.
5. Visit https://ccho4702.github.io after deployment completes.

**Before publishing:** the undergraduate transcript PDF in `assets/pdf/` will be publicly downloadable. Review it and remove or replace any information you do not want to publish. Also review the contact addresses, biography, and publication list.

The source site remains under the [al-folio license](LICENSE).
