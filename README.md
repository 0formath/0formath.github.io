# HYUAISL

Hanyang University AI Systems Lab.

## runnng locally

### install dependencies

```bash
bundle --gemfile Gemfile.local
bundle install --gemfile Gemfile.local
```

### serving at localhost

```bash
BUNDLE_GEMFILE=Gemfile.local bundle exec jekyll serve --config _config_local.yml

# or in windows command line
set BUNDLE_GEMFILE=Gemfile.local
bundle exec jekyll serve --config _config_local.yml
```
