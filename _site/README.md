# The Hacker-Blog theme

## Included
1. Pagination
2. SEO tags
3. Archive Page
4. About Page

## Usage
1. Clone this repository
2. Customize your blog
3. Add posts in `_posts/` directory
4. Commit and push
5. Visit `<githubusername>.github.io`

## Local Build
1. [`gem install jekyll`](https://jekyllrb.com/docs/installation/#install-with-rubygems)
2. `gem install jekyll-seo-tag`
3. `gem install jekyll-paginate`
4. `gem install jekyll-sitemap`
5. `cd <directory>`
6. `jekyll serve --watch --port 8000`
6. Go to `http://0.0.0.0:8000/` in your web browser.

*Note: In case you have set a `baseurl` different than `/` in `_config.yml`, go to `http://0.0.0.0:8000/BASEURL/` instead.*


## Customizing
### Configuration variables
Edit the `_config.yml` file and set the following variables:
```yml
title: [The title of your blog]
description: [A short description of your blog's purpose]
author:
  name: [Your name]
  email: [Your email address]
  url: [URL of your website]

baseurl: [The base url for this blog.]

paginate: [Number of posts in one paginated section (default: 3)]
owner: [Your name]
year: [Current Year]
```

Additionally, you may choose to set the following optional variables:
```yml
google_analytics: [Your Google Analytics tracking ID]
```

### About Page
Edit `about.md`

### Layout
If you would like to modify the site style:

**HTML**  
Footer: Edit `_includes/footer.html`  
Header: Edit `_includes/header.html`  
Links in the header: Edit `_includes/links.html`  
Meta tags, blog title display, and additional CSS: Edit `_includes/head.html`  
Index page layout: Edit `_layouts/default.html`  
Post layout: Edit `_layouts/post.html`  

**CSS**  
Site wide CSS: Edit `_sass/base.scss`  
Custom CSS: Make `_sass/custom.scss` and use it. Then add `@import "custom";` to `css/main.scss`

**404 page**
Edit `404.md`

## License
CC0 1.0 Universal