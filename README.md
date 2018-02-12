# [freeklepikov.org](https://freeklepikov.org/en/)

Support website for jailed for Tor exit relay Dmitry Klepikov.

## How to build and run

```bash
git clone https://github.com/komachi/freeklepikov.org && cd freeklepikov.org
bundle install
bundle exec jekyll serve
```

## How to build and run in [Termux](https://termux.com/)

```bash
apt install git make clang nodejs ruby ruby-dev libffi-dev libxml2-dev libxslt-dev pkg-config
git clone https://github.com/komachi/freeklepikov.org && cd freeklepikov.org
gem install bundle pkg-config
gem install nokogiri -- --use-system-libraries
bundle install
bundle exec jekyll serve
```
