# Vienna

## Overview

Vienna is a simple and clean blog theme for [Hugo](http://gohugo.io/).
Notable features are:

- Simple and clean design
- Client side source code highlighting
- Social links (Twitter, Facebook, GitHub, LinkedIn)
- Support for tags
- Analytics with Mixpanel
- Responsive design
- Font Awesome icons

## Installation

In your hugo site directory, run:

```shell
$ mkdir themes
$ cd themes
$ git clone https://github.com/keichi/vienna
```

## Configuration

You may specify following options in `config.toml` of your site to make use of
this theme's feattures.

```toml
baseurl = "Your site URL"
languageCode = "en-us"
title = "Your site title"
author = "Your Name"
# Copyright notice. This is displayer in the footer.
copyright = "&copy; Copyright notice"

[params]
    # Social accounts. Link to these accounts are displayed in the header and
    # footer. (Optional)
    twitter = "Your Twitter username"
    github = "Your GitHub username"
    linkedin = "Your LinkedIn username"
    facebook = "Your Facebook username"
    # Mixpanel API key. (Optional)
    mixpanel_api_key = "Your Mixpanel API key"
    # Short bio/tagline. This is displayer in the header.
    bio = "Your short bio/tagline"
```

## Usage

Use hugo's `-t vienna` or `--theme=vienna` option with hugo commands.
Example:

```shell
$ hugo server -t vienna -w -D
```

