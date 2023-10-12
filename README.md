 # 3ds.hacks.guide

A  mirror of a complete guide to 3DS (and 2DS) custom firmware, from stock to boot9strap.

[https://funnynnuf.github.io/3d/](https://funnynnuf.github.io/3d/)

## Running the site locally

This requires the following installed on your system:
- ruby(-dev)
- bundler

To test the website locally, simply run the following commands:

```sh
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve
```

The website should now be running on http://127.0.0.1:4000/.
