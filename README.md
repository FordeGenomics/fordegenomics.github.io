# FordeGenomics GitHub Pages

Based on [Jekyll](http://jekyllrb.com/) and the Contrast template. Follow instructions to use this template from the original [repository](https://github.com/niklasbuschmann/contrast) and adjust the `_config.yml` to use with [Github Pages](https://pages.github.com/).

To run locally:

- Clone the repository
- Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
- Run `bundle clean` to clean up the directory (no need to run --force)
- Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
- Run `bundle exec jekyll serve` to generate the HTML and access it from at localhost:4000.
