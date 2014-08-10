# OPML Feed Generator for Jekyll

Jekyll plugin for generating an opml feed for blogs from planet.yml.

If you use [planet.rb](https://github.com/pote/planet.rb) gem to fetch news from other blogs/sources and you want to generate OPML feed for your favourites RSS reader then OPML Generator for Jekyll is for you.

## Installation

In your Jekyll site source root directory, create or open a `_plugins` directory. Paste `opml_generator.rb` there.

## Usage

OPML Generator will create files with `feed.opml` name in root directory and for each category and tag (`/categories/category-name/feed.opml`, `/tags/tag-name/feed.opml` and `/categories/category-name/tags/tag-name/feed.opml`). In your site just add link to OPML feed and all will work now. :+1:
