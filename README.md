# 藤 (Fuji)

Base: [amzrk2/hugo-theme-fuji](https://github.com/amzrk2/hugo-theme-fuji)

## Live demos

[My Portfolio](https://portfolio.39.gy/)

## exsample config.toml

```toml
baseURL = "https://example.com"
title = "Fuji Demo"
theme = "fuji"
hasCJKLanguage = true
enableEmoji = true
enableRobotsTXT = true
disableKinds = ["RSS", "taxonomyTerm"]

## Change this two to switch between different language
## Now support: en, zh-hans, zh-hant, ja
defaultContentLanguage = "en"
languageCode = "en"

summaryLength = 100 # Custom cummary length, add <!--more--> in post file to custom split point
paginate = 10

# googleAnalytics = "UA-000000000-0" # Set your Google Analytics UA here, or comment out to disable

[permalinks]
  post = "/:filename/" # Custom post links, e.g. "/:year/:month/:title/"

[params]
  author = "DSRKafuU" # You can also set author in post front matter individually
  subTitle = "This is a Sub Title"

  # Open Graph & Twitter Card variables
  # You can also set description and images in post front matter individually
  description = "A minimal hugo theme powered by Primer CSS."
  images = ["img/og.png"] # This will use the image called og.png in static/img folder

  # Posts shown in homepage
  mainSections = ["post"]

  # License
  license = "Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)"
  licenseLink = "http://creativecommons.org/licenses/by-nc-sa/4.0/"

  # Comments
  # utterances, see: https://utteranc.es/
  utterancesRepo = "[ENTER REPO HERE]"
  utterancesIssueTerm = "pathname"
  utterancesTheme = "github-light"

[markup]
  [markup.highlight]
    style = "monokailight"

  [markup.tableOfContents]
    startLevel = 2
    endLevel = 2

[taxonomies]
  tag = "tags"

[menu]
  [[menu.nav]]
    name = "Home"
    url = "/"
    weight = 1
  [[menu.nav]]
    name = "Archives"
    url = "/archives/"
    weight = 2
  [[menu.nav]]
    name = "About"
    url = "/about/"
    weight = 3

  [[menu.link]]
    name = "GitHub"
    url = "https://github.com/ress997"
    weight = 1
  [[menu.link]]
    name = "Twitter"
    url = "https://twitter.com/ress997"
    weight = 2
```
