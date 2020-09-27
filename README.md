
## gingeleski.com Hugo theme

This is the Hugo theme of gingeleski, forked off the [Hugo-Casper3](https://github.com/jonathanjanssens/hugo-casper3) port by Jonathan Janssens, which itself was based on [Casper](https://github.com/TryGhost/Casper).

A demo of *that* with feature images is available in the repository [jonathanjanssens/hugo-casper3-demo](https://github.com/jonathanjanssens/hugo-casper3-demo).

## Fork

This was a "hard fork" and is not being kept up-to-date with anything that may be going on in those other themes.

Notable modifications:

- *None yet!*

## Installation

```$ mkdir themes
$ cd themes
$ git clone git@github.com:gingeleski/gingeleski-hugo-theme.git
```

Either set the theme in your config to `gingeleski` or build with the `-t gingeleski` flag.

## Using the theme

This theme is very image heavy so it is recommended to set a `feature_image` parameter in the front matter of any content.

Content types you wish to appear on the homepage should be set in your [mainSections](https://gohugo.io/functions/where/#mainsections).

## Development roadmap

Leftover items from Jonathan Janseens:

[ ] Use SCSS from original theme instead of compiled CSS - also needs Hugo Pipes setting up
[ ] Multi author support and author taxonomy
