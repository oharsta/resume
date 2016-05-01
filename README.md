## [Resume template](#resume-template)

Middleman project with static Resume site.

### [System Requirements](#system-requirements)

- ruby
- npm

### [Install](#install)

```bash
npm install
bundle install --path vendor/bundle
bundle exec middleman
```

To build a new version and deploy to [github.io](http://oharsta.github.io/resume-template/build/)

```bash
git checkout gh-pages
git merge master
bundle exec middleman build
git add .
git commit -am 'new release'
git push
```


