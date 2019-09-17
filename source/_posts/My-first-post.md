---
title: The beginning
date: 2019-08-06 22:12:50
description: Everything that has an ending, has a beginning!
categories: 
tags: [javascript, ES6]
thumbnail: /images/coding3.jpg
---

This is my personal blog. From time to time I write about things related to my passions, mainly coding, photography and music theory. The idea is to have an online personal container for my notes and cheatsheets which i usually forget, to be available for reference in the future years. 
The site is built with [Hexo](https://hexo.io/)!. Check [documentation](https://hexo.io/docs/) for more info. The site is online at the following [address](https://affectionate-cray-b35aba.netlify.com/).

## Usage

``` bash
$ hexo new "My New Post"  // default is 'post'
$ hexo new post "My New Post"
$ hexo new page "Music"
```
Inside the markdown at the very beginning the post details is provided with:
``` markdown
---
title: My first post
date: 2019-08-06 22:12:50
description: An example .....
tags: [test, prova]
thumbnail: https://via.placeholder.com/150
---
```

For images in markdown file:
``` markdown
![coding1](/images/coding1.jpg)
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run development server

``` bash
$ hexo server
```
More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

