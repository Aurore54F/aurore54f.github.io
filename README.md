# [aurore54f.github.io](https://aurore54f.github.io)

Personal web page on GitHub.

This was cloned from https://github.com/academicpages/academicpages.github.io.


## To run locally (not on GitHub Pages, to serve on your own computer)

1. Make sure you have ruby-dev, bundler, and nodejs installed: see `ruby-commands` on MacOS X;
1. Run `bundle clean` to clean up the directory (no need to run `--force`);
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again;
1. Run 
```
rbenv shell 2.6.4
rbenv rehash
bundle exec jekyll liveserve
```
to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.
