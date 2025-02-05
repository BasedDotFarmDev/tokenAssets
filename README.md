# Token Assets

The goal of this project is to unify the cryptocurrency token assets under one
CDN with pragmatic access.

The CDN supports SVG and PNGs (small, larger).

## Usage

Currently the API/CDN endpoint is at:

```
https://assets.smold.app/api/token/[chainID]/[tokenAddress]/[fileName].[ext]
```

## Contributing

You will need an SVG file of the logo of the asset. You can use
[Inkscape](https://inkscape.org/) or a web tool like
https://cloudconvert.com/svg-to-png to convert the SVG file into the PNGs.

With Inkscape you can run:
```
$ inkscape -w 128 -h 128 logo.svg -e logo-18.png
$ inkscape -w 32 -h 32 logo.svg -e logo-32.png
```

Once ready, create a new directory with the chain ID, or use the existing one,
and create a new directory for the token address (in lower case) you are adding.

Fill-in the details when creating the pull-request, and we'll merge it shortly!

That's it, thank you!
