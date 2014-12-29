# Lightpush

Theme used at [Medicor's](http://www.medicor.se) web site. A lighter version of Hexo's default theme [Light](https://github.com/hexojs/hexo-theme-light).

Includes:
* [Slide and Push menus by Codrops](http://tympanus.net/codrops/2013/04/17/slide-and-push-menus/)
* Post searching through [simple post search api](https://github.com/medicor/hexo-filter-api/)

## Install

Execute the following command and modify `theme` in `_config.yml` to `lightpush`.

```
git clone https://github.com/Medicor/Lightpush.git themes/lightpush
```

## Update

Execute the following command to update Lightpush.

```
cd themes/lightpush
git pull
```

## Config

Default config:

``` yaml
menu:
  Home:
    link: /
    icon: fa-home
  Archives:
    link: /archives
    icon: fa-archive

widgets:
- search
- category
- tag

excerpt_link: more ...

twitter:
  username: <your-twitter-name>
  show_replies: false
  tweet_count: 5

addthis:
  enable: true
  pubid: ra-XXXXXXXXXXXXXXXX

fancybox: false

google_analytics: UA-XXXXXXXX-X
rss:

comment_provider:
```

## Features

This theme also supports the following new options in global _config.yml:

``` yaml
logo: <path to image to put in front of site title>
favicon: <path to favicon >
```

[Hexo]: http://hexo.io/
[AddThis]: https://www.addthis.com/dashboard/
