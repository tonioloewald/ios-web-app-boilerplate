# ios-web-app-boilerplate

[See it in action](https://tonioloewald.github.io/ios-web-app-boilerplate/)

I was surprised this doesn't seem to exist in useful form anywhere, so whipped this up.
It makes extensive use of css-variables, which should allow it to adapt to different mobile
devices and OS versions pretty easily. Where possible, I pulled values direct from Apple HIG
or by measuring screenshots.

- My goal is for this to function as _universal_ boilerplate, so I've added `:hover` and `:active`
styles so that widgets look better on desktops.
- Yes, it already supports darkmode (via. css-variable overrides)
- I think maybe the size variations should be implemented as classes with css-variable overrides.

Based on (but not a fork of) [html5-boilerplate](https://github.com/h5bp/html5-boilerplate).
