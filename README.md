# flag-icons

A collection of all country flags in SVG — plus the CSS for easier integration.

## Usage

For using the flags inline with text add the classes `.flag-icon` and
`.flag-icon-xxx` (where `xxx` is the
[ISO 3166-1-alpha-3 code](https://www.iso.org/obp/ui/#search/code/)
of a country) to an empty `<span>`. If you want to have a squared version flag
then add the class `flag-icon-squared` as well. Example:

```html
<span class="flag-icon flag-icon-gr"></span>
<span class="flag-icon flag-icon-gr flag-icon-squared"></span>
```

You could also apply this to any element, but in that case you'll have to use the
`flag-icon-background` instead of `flag-icon` and you're set. This will add the
correct background with the following CSS properties:

```css
background-size: contain;
background-position: 50%;
background-repeat: no-repeat;
```

Which means that the flag is just going to appear in the middle of an element, so
you will have to set manually the correct size of 4 by 3 ratio or if it's squared
add also the `flag-icon-squared` class.

## Credits

Many thanks to [lipis](https://github.com/lipis) for his repository, from which almost all the content was taken. Some flags have been added or changed. The alpha-2 code for alpha-3 has been replaced. The project is compiled using SASS.