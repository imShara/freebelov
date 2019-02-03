![Free Fedor Vlasov — #freeVlasov](images/freevlasov-en.jpg)

# [freevlasov.info](https://freevlasov.info/)

Support website about jailed russian [software developer](https://tjournal.ru/law/86639-vtoroy-bogatov-istoriya-sozdatelya-alternativnogo-klienta-dlya-vkontakte-kate-mobile-kotoryy-tretiy-mesyac-sidit-v-sizo) Fedor Vlasov.

## How to build and run

```bash
git clone https://github.com/imShara/freevlasov.info && cd freevlasov.info
bundle install
bundle exec jekyll serve
```

## How to build and run in [Termux](https://termux.com/)

```bash
apt install git make clang nodejs ruby ruby-dev libffi-dev libxml2-dev libxslt-dev pkg-config
git clone https://github.com/imShara/freevlasov.info && cd freevlasov.info
gem install bundle pkg-config
gem install nokogiri -- --use-system-libraries
bundle install
bundle exec jekyll serve
```
