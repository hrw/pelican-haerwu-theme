# Haerwu

Haerwu is a theme for the Pelican static site generator. Inspired by
[Spacious](https://themegrill.com/themes/spacious/) theme for WordPress.


# Live example

I use this theme on my [personal
blog](https://marcin.juszkiewicz.com.pl/).


# Installation

[Pelican-Docs](https://docs.getpelican.com/en/stable/) will guide you through the initial installation.


## Plugins

There is support for several plugins:

- neighbors
- read_more (not published yet)
- related_posts
- series


## Configuration

There are several items in theme which should be more configurable. Going
through them in spare time.

Current options:

- THEME_THUMBNAIL - 512x512 picture used for thumbnail in social media
- THEME_THUMBNAIL_192 - 192x192 version of above as some places uses small one
- THEME_SIDEBAR_ABOUT - HTML (needs to have &lt;p&gt; block) for "About me" part in sidebar (optional)
- THEME_SIDEBAR_LINKS - dict of links for sidebar section (optional)
- THEME_FOOTER - HTML for message in the footer (optional)
- THEME_MASTODON_LINK - URL to Mastodon/Fediverse profile
- THEME_USE_READ_MORE - enable short entries on main page
- THEME_INDEX_SHOW_ARTICLE_FOOTER - enable author/date footer on main page
