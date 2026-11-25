# Founder Tribe

The marketing website for ⛺ Founder Tribe, at [foundertribe.org](https://foundertribe.org/).

It's a [Jekyll](https://jekyllrb.com/) site on GitHub Pages. GitHub builds it on every push to `main`, so there's nothing to build or upload yourself.

## What's where

| Folder | What's in it |
|---|---|
| `index.html` | Home page |
| `about`, `events`, `join`, `partners`, `the-tribe`, `ventures` | The other pages |
| `pitch-profiles` | Founder and venture profiles, embedded from Airtable |
| `_layouts`, `_includes` | Page templates, and the parts they share, such as the menu and footer |
| `assets` | CSS, fonts, images and scripts |
| `_config.yml` | Site title, address and social links |
| `CNAME` | The domain. Don't delete it, or the site loses its address |

## Making a change

Edit the file on GitHub, or push to `main`. The site usually updates within a few minutes.

## Previewing on your computer

You need [Ruby](https://www.ruby-lang.org/en/documentation/installation/) and Bundler:

```bash
bundle install
bundle exec jekyll serve
```

Then open http://127.0.0.1:4000/. It builds into `_site`, which isn't committed.

The versions in `Gemfile.lock` were last updated in January 2020 and may not install on a current Ruby. If they don't, run `bundle update`.
