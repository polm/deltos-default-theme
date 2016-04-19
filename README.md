# Deltos Default Theme

This is the default theme for Deltos. It'll work out of the box, but you might want to change some things. Right now a lot of this is manual, but hopefully it'll be automated soon.

### single.html

This is the template for pages on your site. Things to change:

1. The basic page title: `<title>` 
2. The footer section (look for `id="footer"`
3. Twitter Card metadata; look for `XXX`
4. Copyright claim at the bottom (look for `Kopyleft`)

### Favicons

All the favicons default to the Deltos logo. Modern favicons are very complicated, so you may want to use a generator tool. 

### CSS Colors

These are at the top of `style.scss`, which is a [SASS](http://sass-lang.com/) stylesheet. You'll need to use SASS to regenerate `style.css` after modifying the colors.

# License

WTFPL, do as you please. -POLM
