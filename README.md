# preamble

build with [preamble-stitch](https://github.com/derpz-discord/preamble-stitch)

the output file is `output.sty` - you can just upload this to TeXit

## repository layout

`stitchconfig.yml` - configures the preamble stitcher to build an output file

- `main.sty` - The "header", contains the packages to import
- `[subject].sty` - contains useful macros pertaining to [subject]
- `*.package.sty` - contains code which basically provides a whole package
- `factoid.sty` - contains factoids
- `*.factoid.sty` - longer factoids
