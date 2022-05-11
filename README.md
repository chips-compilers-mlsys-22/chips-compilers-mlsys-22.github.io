# Readme

Build locally

```bash
bundle install
bundle exec jekyll serve
```

For Mac M1 users, you will need to update Ruby version to 3.0.0. Homebrew is recommended for upgrading Ruby.

```bash
brew install rbenv ruby-build
rbenv install 3.0.0
rbenv global 3.0.0
echo 'eval "$(rbenv init - bash)"' >> ~/.bash_profile
source ~/.bash_profile
```
