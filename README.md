# Brian A. Yuan — personal website

Built on the [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll theme by Yaoyao Liu.

## Editing

| What | Where |
| --- | --- |
| Name, position, affiliation, email, links, photo, fonts, dark mode | `_config.yml` |
| Bio, education, any other sections | `index.md` |
| Publications | `_data/publications.yml` |

## Running locally

Needs Ruby 3+ (`brew install ruby`).

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/.

## Deploying

Push to GitHub and enable GitHub Pages in the repository settings (deploy from the `main` branch).
