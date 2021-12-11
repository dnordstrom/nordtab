# NORDtab

The simplest `about:newtab` page I could make. Just a [Nord](https://www.nordtheme.com) colored blank page (light or dark depending on browser setting). Adding a `#photo` location hash gives a random gray-scale background photo from [Unsplash](https://unsplash.com) via [Picsum](https://picsum.photos).

## Why?

Because I use the keyboard to navigate either via [Tridactyl](https://github.com/tridactyl/tridactyl) or the URL bar, but add-ons don't work on `about:newtab` and `about:blank` requires `userContent.css` to change colors which is not very portal.

Mozilla doesn't let you set a custom URL for new tabs, only for windows. Tridactyl sets one by default to make the add-on work on new tabs, and you can change it using the `newtab` setting via configuration file or `set newtab [URL]`.

This way things work regardless of if I hit `Ctrl+T` or use Tridactyl's `:tabopen`, on a page I can change with a simple location hash depending on mood. Without another add-on with a thousand features I don't need!

And yes, all of this is ridiculous.
