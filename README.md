# Marc Dordal i Carreras

Personal academic website built with Jekyll and deployed with GitHub Pages.

## Local preview

1. Install Ruby and Bundler.
2. Run `bundle install`.
3. Start the site with `bundle exec jekyll serve`.
4. Open `http://127.0.0.1:4000/`.

If port `4000` is already in use, run `bundle exec jekyll serve --port 4001` instead.

## Repository layout

- `_pages/`: main site pages
- `_published_papers/`, `_policy_papers/`, `_working_papers/`, `_works_in_progress/`: research collections
- `files/`: downloadable PDFs and other attachments
- `images/`: site images and icons
- `markdown_generator/`: optional notebooks and TSV helpers for generating publication entries

## Notes

- Changes to `_config.yml` require restarting the local Jekyll server.
- GitHub Pages builds the production site from the committed Jekyll source in this repository.
