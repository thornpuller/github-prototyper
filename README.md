---
title: GitHub Prototyper
layout: plain
---

# GitHub Prototyper

This tool allows you to easy create and update Web pages and publically host them on GitHub pages.

If you don't have write access to this repository, then you could [fork it](https://help.github.com/articles/fork-a-repo/) to create a copy under your own GitHub account.

Pages can be added by [creating a new file](https://github.com/blog/1436-moving-and-renaming-files-on-github) with the `md` extension. Then simply type your content in the file using the '[Markdown](https://help.github.com/articles/github-flavored-markdown/)' syntax.

You can create folders and link to other pages - see the '[hello world example](http://matharden.github.io/github-prototyper/hello-world-example)' example. You can also put <abbr title="HyperText Mark-up Language">HTML</abbr> in here if you need to.

That stuff at the top of the file is called '[front matter](http://jekyllrb.com/docs/frontmatter/)' which is basically settings for your page, like chosing a template, as well as other options that may be available in a custom template (as a developer if you're not sure). Most commonly '`title`' allows you to set the text which appears in the tab (or top of) your browser.

By the way, this is the '`plain`' HTML `layout`, which has a GitHub appearance.

## Front matter options

### govuk

All are optional except `layout`.

Variable      | Description
------------- | -----------
layout        | name of the template `govuk`
title         | Page title appears in 
subheader     | 4. Sending money
breadcrumbs   | a list of links. List each line with a hyphen. Each link has a text, followed by a colon, then the link. E.g `- Home: https://www.gov.uk/`
jumplinks     | a list of links (as above)
related       | has three sub-items:<br> `title` - the heading on the related info<br>`links` - a list of links<br>`more` - just a link at the end
previous      | has two sub-items:<br> `text` - text label<br>`link` - a link
next          | has two sub-items:<br> `text` - text label<br>`link` - a link

## For developers…

### Running locally

Requires Ruby and Bundler.

```shell
bundle install # get dependancies
jekyll serve # run local server
```
