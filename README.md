# Lightpush

Theme used at ![Medicor](http://www.medicor.se)'s web site.

Includes:
* ![Slide and Push menus by Codrops](http://tympanus.net/codrops/2013/04/17/slide-and-push-menus/)

## Install

Execute the following command and modify `theme` in `_config.yml` to `light`.

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
  Home: /
  Archives: /archives

widgets:
- search
- category
- tag
- twitter

excerpt_link: More

twitter:
  username:
  show_replies: false
  tweet_count: 5

addthis:
  enable: true
  pubid:
  facebook: true
  twitter: true
  google: true
  pinterest: true

fancybox: true

google_analytics:
rss:
```

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **twitter** - Twitter widget config
  - **username** - Twitter username
  - **show_replies** - Enable displaying replies
  - **tweet_count** - Tweets display in widget
- **addthis** - Share buttons at the buttom of articles (Powered by [AddThis])
  - **enable** - Enable share buttons
  - **pubid** - Profile ID of [AddThis]
  - **facebook** - Enable Facebook button
  - **twitter** - Enable Twitter button
  - **google** - Enable Google+ button
  - **pinterest** - Enable Pinterest button
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)

## Features

### Gallery Post
```
---
layout: photo
title: Gallery Post
photos:
- http://i.minus.com/ibobbTlfxZgITW.jpg
- http://i.minus.com/iedpg90Y0exFS.jpg
---
```

### Link Post
```
---
layout: link
title: Link Post
link: http://www.google.com/
---
```

[Hexo]: http://zespia.tw/hexo/
[AddThis]: https://www.addthis.com
[Fancybox]: http://fancyapps.com/fancybox/