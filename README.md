# qer theme
It's a simple dark theme for pelican.

Not with fancy stuff, just a plain theme without the need for huge
modifications and keeping it really light.

There's no `links`. I could implement it on the future. But you
can aways fork the repo and make your own changes and use it.

#### Configuration
On `pelicanconf.py` the following changes are recommended.

- `STATIC_PATHS`, make it point to where are you storing your images;

- `COVER` [False or True], to enable the covers on the top of posts, you need
  to put a `cover: [path from the STATIC_PATHS]` on the header of the post if
  you are using this option;

- `DEFAULT_PAGINATION` I recommend a number depending on the size of summary of
  your posts. I personally use 7;

- `SUMMARY_MAX_LENGHT` just use a number that you feel comfortable with and
  make the visual on the page good;

- `DEFAULT_DATE_FORMAT` use a short one, because the archive was made for
  short formats.

#### Information
The links are all in Portuguese, if you want to change it to your language,
most of it it's under the `templates` folder.

The `TAGLINE` is on the footer of the page.

The CSS was written using [Stylus](http://learnboost.github.io/stylus/), you
don't need to compile it and can aways change directly the `static/style.css` file.

#### Preview
You can have a live preview of my blog, hosted on [here](http://solaire.ml), it's in
Portuguese, but you can get an idea on how it looks.

