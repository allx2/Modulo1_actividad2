## Modulo 1 Actividad 2

The way that you have to publish your github web site has changed.

Now it requires a few more steps than we saw on the video

### Setting up repository

Now we have to set up the repository:

1. Click on settings  
2. Go to Github pages section  
3. Choose the branch and directory that contain the web page  
![](https://s3.amazonaws.com/presales.training/github_page_1.png)

### Jekyll Themes

just add a `_config.yml` to your repository with 
the name of the theme that you want to use and set up the name. eg

```ruby 
title: Example 1
email: user@example.com
description: >- # this means to ignore newlines until "baseurl:"
baseurl: "" # the subpath of your site, e.g. /blog
url: "" # the base hostname & protocol for your site, e.g. http://example.com
github_username:  allx2
theme: jekyll-theme-hacker
```

and push into the repository

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

> _or just ask in the forum_
