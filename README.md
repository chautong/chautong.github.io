# Chau Tong — academic website

Source for [chautong.github.io](https://chautong.github.io/), Chau Tong’s faculty website at the University of Missouri.

## Current content

- Home: `_pages/about.md`
- Research: `_pages/research.md`
- Publications: `_pages/publications.md`
- Teaching: `_pages/teaching.md`
- CCT Lab: `_pages/lab.md`
- News & Recognition: `_pages/news-talks.md`
- CV: `_pages/cv.md`

Navigation is defined in `_data/navigation.yml`; news entries are in `_data/news.yml`. Shared page components are in `_includes/`, and site styling is in `_sass/_site-refresh.scss`.

The public CV uses the neutral filename `files/pdf/Chau_Tong_CV.pdf`.

## Build check

Use the dependencies specified in `Gemfile.lock`, and preserve that lockfile. From this repository’s root:

```sh
bundle install
JEKYLL_ENV=production bundle exec jekyll build --safe
```

Generated `_site/` output, local Bundler configuration, installed dependencies, and build caches are excluded from Git. Keep retired page copies, backup archives, and temporary previews outside this source tree. GitHub Pages publishes the current `master` branch.

## Theme provenance

Built on [AcademicPages](https://github.com/academicpages/academicpages.github.io) and [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes). Original theme licensing is retained in `LICENSE`; font licensing is retained with the font files.
