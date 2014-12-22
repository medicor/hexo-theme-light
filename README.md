# Lightpush

Theme used at [Medicor's](http://www.medicor.se) web site. A lighter version of Hexo's default theme [Light](https://github.com/hexojs/hexo-theme-light).

Includes:
* [Slide and Push menus by Codrops](http://tympanus.net/codrops/2013/04/17/slide-and-push-menus/)

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
- social
- category
- tag

excerpt_link: More ...

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

google_analytics:

rss:
```

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

[Hexo]: http://hexo.io/
[AddThis]: https://www.addthis.com/dashboard/
