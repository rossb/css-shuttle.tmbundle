# CSS Shuttle

TextMate 2 bundle to supplement TextMate's default CSS bundle with gradients, transforms, animations, media queries and other modern and specialised CSS features and patterns.

Also includes snippets for basic CSS properties with the aim of maximum authorship speed, based on years of experience with the most common usage patterns for properties & values.

As a general rule vendor prefixes are excluded: I recommend using something like Autoprefixer (https://github.com/postcss/autoprefixer) during your build process, rather than including vendor prefixes directly in your stylesheets.

I also avoid including snippets for unstable or experimental CSS features that have yet to be widely implemented across major browsers, unless they are stable enough in some browsers to serve a purpose in production use today, e.g. as part of a progressive enhancement.