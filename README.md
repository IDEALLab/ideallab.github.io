# The IDEAL Lab main website

## TO-DOs

See Issues on [the site](https://github.com/IDEALLab/ideallab.github.io).

## Build site

To build the website locally, clone the repo with:

```
git clone https://github.com/IDEALLab/ideallab.github.io.git
```

Then install necessary Ruby dependencies by running `bundle install` from within the `ideallab.github.io` directory.  After this, the site can be be built with:

```
bundle exec jekyll build
```

(If you are getting errors at this stage, it may be due to your version of `bundle`. Try `gem uninstall bundler` + `gem install bundler -v 1.13.1`.)

To view the site, run `bundle exec jekyll serve` and point a browser to `http://localhost:4000/`.  More information on Jekyll can be found [here](http://jekyllrb.com/).

To include projects, preprocessing scripts are necessary to clone project repos and update Jekyll metadata. This can be accomplished with:

```
ruby _scripts/update-and-preprocess.rb
```

Then `jekyll build` works as normal.

## Contribute

Blog posts just require YAML top matter that looks something like:

```
---
layout: post
title: Your Title
author: Mark Fuge
link: https://enme.umd.edu
image: /images/path/to/image.png
---
```

The `layout`, `title` and `author` tags are required, while `link` and `image` are optional.  Just save a Markdown file with this top matter as something like `blog/_posts/YYYY-MM-DD-blog-title.md`, where `YYYY-MM-DD` is the date of the post and `newton-institute` is the `blog-title`.  This short title is used in the URL of the post, so this becomes `blog/blog-title/`, so the short title should be long enough and unique enough not to cause conflicts with other posts.

## For more information

* Look over the [metadata format guide](http://bedford.io/guide/format/)
* Look over the [Markdown style guide](http://bedford.io/guide/style/)

## License

[MIT](http://opensource.org/licenses/MIT)
