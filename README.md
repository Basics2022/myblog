
# README

## Blogging with Quarto
Basics blog with Quarto.

Why Quarto? At a first impression, it looks good and with all the features I need, as described by Mark Isken on its blog [Bits of Analytics](https://bitsofanalytics.org/posts/port-to-quarto/).

Hoping that this will feel like a clean extension of a Jupyter Book with fancy tools blog at the minimum pain, like tags and automatic layout of the main page with latest posts. That's all I need here: just a tool blog made with .md and .ipynb, to be publicly hosted on GitHub, allowing comments.

Here I'll list some useful comments and references

## Setup and create

### Setup Quarto

#### Download sources

Download .deb or .tar from the official website.

#### Create project

> quarto create-project myblog --type website:blog

**!** It looks like *website:blog* doesn't exist, but *--type website* does

### Setup

#### Create and setup GitHub repo
...

#### Create GitHub action

Create branch *gh-pages*, and create GitHub action for updating deplyed website.

...

#### ...
...

### Create posts

> quarto create post "Title"

**!** Not working with my current installation. Just create a folder containing an *index.qdm* or *index.ipynb* file for the post, and everything else is required (images, and other sources).

### Git add, commit, push and publish

> git add .
> git commit -m "..."
> git push

> quarto publish gh-pages


## References and Examples
* https://quarto.org/
* https://quarto.org/docs/websites/website-blog.html
* https://bitsofanalytics.org/
* https://beamilz.com/

