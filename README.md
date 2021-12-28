# NORDtab

The simplest `about:newtab` page I could make: just a Nord colored blank page. Using a `#photo` location hash makes it pull a random gray-scale photo from [Unsplash](https://unsplash.com).

## Why?

Because I use the keyboard to navigate either with [Tridactyl](https://github.com/tridactyl/tridactyl) or the URL bar so I want a simple page with no buttons, but add-ons don't work on `about:newtab` and `about:blank` requires `userContent.css` to change colors which is not very portable.

Mozilla doesn't let you set a URL for new tabs, only for windows. Tridactyl sets one by default to make the add-on work on new tabs. It doesn't look very nice, but you can change it using the `newtab` setting via configuration file or `set newtab [URL]`.

This way things work regardless of if I use `Ctrl+T` or Tridactyl's `:tabopen`, and I have a page I can change with a simple location hash depending on mood.

And yes, all of this is ridiculous.

## Credits

Thanks to [Arctic Ice Studio](https://www.arcticicestudio.com/) for the great [Nord theme](https://www.nordtheme.com/), [Picsum](https://picsum.photos/) for their super simple API, and to everyone sponsoring and contributing to [Tridactyl](https://github.com/tridactyl/tridactyl), arguably the most useful browser add-on in existence.
