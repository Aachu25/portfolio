# Portfolio Site

This repository contains my personal portfolio built with [Jekyll](https://jekyllrb.com/) and the Hacker theme. It showcases projects, education, and volunteering information.

## Prerequisites

- **Ruby** 2.7 or higher
- **Jekyll** and **Bundler** gems (`gem install jekyll bundler`)

## Building and Running Locally

1. Clone this repository.
2. Install required Ruby gems: `bundle install` (or run `jekyll serve` directly if no Gemfile is present).
3. Start the local server with:

   ```bash
   bundle exec jekyll serve
   ```

   The site will be available at `http://localhost:4000`.

## Deploying

Push changes to the `main` branch and enable GitHub Pages for automatic deployment. Any static host that supports HTML can also serve the generated `_site` directory.

## Customization & Folder Structure

- **_config.yml** – Site settings such as title, description, and theme.
- **index.md** – Main landing page content.
- **assets/** – Images and other static files used by the site.

Edit `index.md` and update images in `assets/img/` to customize the portfolio. Adjust settings in `_config.yml` to change the title, logo, or theme.
