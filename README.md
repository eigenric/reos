# YOUNGEEK-THEME

youngeek-theme is a responsive theme for [Pelican](http://getpelican.com).

## DEMO

You can see the [theme in action](http://www.youngeek.tk).

## FEATURES

- responsive
- syntax highlighting for pre blocks
- supports google analytics
- custom list of links

## INSTALL

Clone the [repository](https://github.com/riki319/youngeek-theme),
edit your `pelicanconf.py` and modify the `THEME` variable to make it 
point to the downloaded theme location, or install it with the `pelican-themes` command tool.


## PELICANCONF.PY

Supports a number of common global variables but patches are welcomed if you need better support.

- `GOOGLE_ANALYTICS` your code

- `USER_LOGO_URL`  SITEURL + '/static/images/your_logo.png'
- `DISQUS_SITENAME` set this to enable disqus comments in articles
- `COLLAPSE_COMMENTS` set to `True` to have article comments hidden by default. Clicking on the `comments` link will toggle visibility.
- `TAGLINE` some text rendered right below the logo
- `INTERNET_DEFENSE_LEAGUE` set this to `True` if you want to enable the [Internet Defense League](http://internetdefenseleague.org) code
When developing locally, you may want to set the following variable: `SITEURL = http://localhost:8000`


## AUTHOR

youngeek-theme is authored by Ricardo Ruiz.
