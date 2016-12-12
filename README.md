# Azulite

Azulite is a simple, minimal Jekyll theme. Preview at [mattmflowers.com/azulite](https://mattmflowers.com/azulite)

## Running locally

Make sure you have all the Jekyll requirements installed and clone the project.

```bash
git clone git@github.com:flattmo/azulite.git
```

Navigate into the directory you cloned the theme into and run `bundle install`
 to install the Gemfile dependencies.

You can add markdown files to the `_posts` folder to have them appear on the
homepage.

Build and serve the site locally with:

```bash
bundle exec jekyll serve
```

## Deploying to gh-pages

Before deploying to gh-pages, you must comment out the line `gem "jekyll", "3.3.1"`
in the Gemfile and uncomment the line `gem "github-pages", group: :jekyll_plugins`.

Then make sure your `_config.yml` file is completely filled out and push to your
gh-pages repo/branch.