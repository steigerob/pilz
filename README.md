## Local preview

```bash
# install Ruby & Bundler (Ubuntu)
sudo apt update
sudo apt install ruby-full build-essential zlib1g-dev

# in the project folder
gem install bundler
bundle install
bundle exec jekyll serve --livereload
```

Open http://127.0.0.1:4000

If you publish on GitHub Pages as a *project* site, set `baseurl` in `_config.yml` to `"/REPO-NAME"` and `url` to your site URL. For a *user* site (username.github.io), leave `baseurl` empty and set `url` to `https://username.github.io`.

