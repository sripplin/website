# steveripplinger.com
This is my website repo for https://www.steveripplinger.com


## Intro


## Setup
I mostly followed [this guide](https://www.youtube.com/watch?v=UKB9ylw0G4U) to setup Ruby and Jekyll on my mac. [This guide](https://www.youtube.com/watch?v=EmSrQCDsMv4) also helped. [This repo](https://github.com/robertmartin8/ReasonableDeviations) also had some good additional modifications that I incorporated and where I got a lot of inspiration.

## Theme & Style
I decided on [Hyde](https://github.com/poole/hyde) as a nice, two-column theme. It is simple and I can easily customize the colors and any css as needed.

Other themes I considered were [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy/) and [minimalist](https://github.com/BDHU/minimalist).

I performed a lot of modifications including:
- changing theme colors, font colors, link colors
- fonts
- enabled font awesome for icons
- optimized website for mobile, since this theme is quite old the sizing didn't translate well to mobile.
  - optimized font sizes for web and mobile
  - made images responsive to sizing for web and mobile
- snippits on home page instead of full posts
- added featured image to post previews on home page (though toggled off)
- added button via javascript to scroll [back to top](https://github.com/vfeskov/vanilla-back-to-top) for posts
- Added dark mode. Takes OS preference plus a toggle with persistance. [This](https://github.com/derekkedziora/jekyll-demo) repo was the biggest help.

### Fonts


### Color

I'm a big fan of blue so went with a nice navy shade. The sidebar looked a little plain so I added a diagonal gradient.

## Other Notes
I also had to deal with 301 redirects with this [solution](https://github.com/jekyll/jekyll-redirect-from).

Pointing domain name was relatively easy.

## Resources & References
https://github.com/BillRaymond/install-jekyll-apple-silicon/blob/main/README.md
https://github.com/robertmartin8/ReasonableDeviations

## License
Code for the website can be reproduced with attribution and without warranty, under the MIT license.

Content is copyright per <a href="/disclaimer">Disclaimer.</a>
