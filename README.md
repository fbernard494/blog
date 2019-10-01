# Dromotherm

site for dromotherm.fr

http://dromotherm.github.io/blog

## Reminder - how to write posts

### place to deposit 
Posts are stored in the [_posts directory](/_posts)

### name and metadatas
A new post must be named :	AAAA-MM-DD-name_bla_bla.markdown

The file must start with a metadatas header
```
---
layout: post
title:  "Welcome !"
date: AAAA-MM-DD
categories: [project management, other category]
---
```
Date and categories are optional

The post has to be written in the markdown syntax

### structure
```
# title
## subtitle
```

### Insert a link :
```
[text - description of the link](http://www.cerema.fr)
```

### Manage and insert images

Images are to be stored in the [assets directory](/assets)

To upload a new image with the github web UI
![upload new image via UI 1](/assets/doc/upload_illustration_1.png){:class="img-responsive"} 
![upload new image via UI 2](/assets/doc/upload_illustration_2.png){:class="img-responsive"} 

To insert a new image in a post, in a responsive manner (ie for mobile and desktop client)
```
![image description]({{ site.baseurl }}/path/to/image){:class="img-responsive"} 
```
For example /path/to/image can be `/assets/smartgrid.png`
