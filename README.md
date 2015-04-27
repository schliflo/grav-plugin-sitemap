# Grav Sitemap Plugin

`Sitemap` is a [Grav](http://github.com/getgrav/grav) Plugin that generates a [map of your pages](http://en.wikipedia.org/wiki/Site_map) in `XML` format that is easily understandable and indexable by Search engines.

## GPM Installation (Preferred)

The simplest way to install this plugin is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install sitemap

This will install the Sitemap plugin into your `/user/plugins` directory within Grav. Its files can be found under `/your/site/grav/user/plugins/sitemap`.

## Manual Installation

To install this plugin, just download the zip version of this repository and unzip it under `/your/site/grav/user/plugins`. Then, rename the folder to `sitemap`. You can find these files either on [GitHub](https://github.com/getgrav/grav-plugin-sitemap) or via [GetGrav.org](http://getgrav.org/downloads/plugins#extras).

You should now have all the plugin files under

    /your/site/grav/user/plugins/sitemap

>> NOTE: This plugin is a modular component for Grav which requires [Grav](http://github.com/getgrav/grav), the [Error](https://github.com/getgrav/grav-plugin-error) and [Problems](https://github.com/getgrav/grav-plugin-problems) plugins, and a theme to be installed in order to operate.


# Usage

The `sitemap` plugin works out of the box. You can just go directly to `http://yoursite.com/sitemap` and you will see the generated `XML`.

# Config Defaults

```
enabled: true
route: '/sitemap'
ignores:
  - /blog/blog-post-to-ignore
  - /ingore-this-route
```

You can ignore your own pages by providing a list of routes to ignore.
