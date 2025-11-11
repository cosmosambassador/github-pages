# Jet Services Eco System

This repository hosts the source for the Jet Services Eco System GitHub Pages site. The site aggregates documentation for the
Jet Services mission control agents—UMEJETUS, Unity Flame, and GPT Icon—alongside governance playbooks and the 150 Capstone
initiative tracker.

## Structure

- `_config.yml` – Jekyll configuration using the Cayman theme and custom collections for guides.
- `index.md` – Landing page with quick links to each mission control workspace.
- `guides/` – Deep-dive guides for agents, capstone tracking, and launch operations.
- `_posts/` – Announcements and release notes for ecosystem updates.

## Local Development

1. Install Ruby (>= 3.0) and Bundler.
2. Run `bundle install` to fetch dependencies.
3. Serve the site locally with `bundle exec jekyll serve` and open `http://127.0.0.1:4000`.

## Deployment

Pushes to the default branch trigger GitHub Pages to build and deploy the site automatically. Ensure that the repository is
configured to use GitHub Actions and the `GitHub Pages` workflow is enabled.
