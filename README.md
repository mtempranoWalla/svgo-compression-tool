# svgo-compression-tool

Uses svgo standard compression plugins but removes the default `removeViewBox` so that the svgs maintain their scalable properties.

## how to use

Add an `origin-folder` and `destination-folder` folders to the project root and add the svg you want to compress in the `origin-folder`.
Run `yarn compress`