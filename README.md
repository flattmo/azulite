# Azulite

Azulite is a lite, minimal Jekyll theme with a simple, yet elegant, colorscheme. Preview [here](https://mattflow.github.io/azulite)

## Running locally

Make sure you have all the Jekyll requirements installed and clone the project.

```bash
git clone git@github.com:flattmo/azulite.git
```

Navigate into the directory you cloned the theme into install the Gemfile dependencies
using:

```bash
bundle install
```

Build and serve the site locally with:

```bash
bundle exec jekyll serve
```

You can now add markdown files to the `_posts` folder to have them appear on the
homepage.


## Deploying to gh-pages

Before deploying to gh-pages, you must comment out the line `gem "jekyll", "x.x.x"`
in the Gemfile and uncomment the line `gem "github-pages", group: :jekyll_plugins`.

Then make sure your `_config.yml` file is completely filled out and push to your
gh-pages repo/branch.
