# Codexe

This is a HEXO theme which is similar with GitBook

- [Preview](http://www.codexe.net)

## Installation

### Install

``` bash
$ git clone https://github.com/codexehan/codexe.git themes/codexe
```

### Enable

Modify `theme` setting in `_config.yml` to `codexe`.

### Update

``` bash
cd themes/codexe
git pull
```

## Configuration

``` yml
# Miscellaneous
google_analytics:
gauges_analytics:
favicon: /favicon.png
twitter:
google_plus:
fb_admins:
fb_app_id:
```

- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
- **twitter** - Twiiter ID
- **google_plus** - Google+ ID

## Features

One of the main features of codexe is the left sider. To generate the left sider, especially how to group different posts, you need use **categories** (generate book name) and **chapter** (generate chapter in a book).
### Book Name

You can use **categories** to set the book name in the post. Codexe will group all the posts with same category.

**It would be better to add one category for every post. For posts without category will be grouped by default category.**

```
categories:
- book name
```

### Chapter Name

You can use **chapter** to set the chapter name in the post. Codexe will group all the posts with same chapter in a book.

```
chapter: chapter name
```

