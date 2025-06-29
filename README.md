<div align="center">
<h1>dwlb</h1>

A fast, feature-complete bar originally for dwl, modified to work with maomaowm

</div>

## Dependencies
* libwayland-client
* libwayland-cursor
* pixman
* fcft

## Installation
```bash
git clone --single-branch --branch mao https://github.com/droc12345/dwlb
cd dwlb
make
make install
```

## Usage
Pass `dwlb` as an argument to maomao's `-s` flag. This will populate each connected output with a bar. For example:
```bash
maomao -s 'dwlb -font "monospace:size=16"'
```
## Other Options
Run `dwlb -h` for a full list of options.

Note: Not all options tested with maomao, so not sure if they work.
They are the x, y, width, height and layer change options.

I'm not really working much on this other than what's already done, as I'm not running the current version of maomao.
