# This is a version of the site from before ["The Great MSET9" purge](https://github.com/hacks-guide/Guide_3DS/pull/2393)
It will get updated with the latest changes while keeping all of the other methods that got purged. The purged methods ***WILL NOT*** be updated. For updated info, go to [wiki.hacks.guide](https://wiki.hacks.guide/wiki/3DS:Alternate_Exploits).

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
