# hugo-vue-mix
A simple Hugo theme for tech blog, Powered by Vue.js and Vuetify.

## Install
```
cd ./themes
https://github.com/mikanbearer/hugo-vue-mix
```

## config.toml example
```toml
baseURL = "https://mikanbearer.github.io/hugo-vue-mix"
languageCode = "en-us"

DefaultContentLanguage = "en"
title = "活到老學到死"
theme = "hugo-vue-mix"
metaDataFormat = "yaml"

disqusShortname = "mikanmimi"
disablePathToLower = true

[markup]
  [markup.goldmark]
    [markup.goldmark.renderer]
      unsafe = true
  
[Params]
  keywords = "tech-note"
  description = "只是筆記"
  mainSections = ["post","posts"]
  favicon = "img/favicon.ico"
  dateFormat = "January 2, 2006"
  comments = true
  readingTime = true
  wordCount = true
  socialShare = true
  delayDisqus = true
  showRelatedPosts = true
  preserveTaxonomyNames = true

[outputs]
  home = ["HTML"]
  page = ["HTML"]
  section = ["HTML"]

[Author]
  name = "Zhang San"
  imageURL = ""
  email = ""
```

## License

Released under the MIT License.

## Demo

[活到老學到死](https://mikanbearer.github.io/hugo-vue-mix)
