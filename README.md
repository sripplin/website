# steveripplinger.com
This is my website repo for https://wwww.steveripplinger.com


## Intro


## Setup
I mostly followed [this guide](https://www.youtube.com/watch?v=UKB9ylw0G4U) to setup Ruby and Jekyll on my mac. [This guide](https://www.youtube.com/watch?v=EmSrQCDsMv4) also helped. [This repo](https://github.com/robertmartin8/ReasonableDeviations) also had some good additional modifications that I incorporated and where I got a lot of inspiration.

## Theme & Style
I decided on [Hyde](https://github.com/poole/hyde) as a nice, two-column theme. It is simple and I can easily customize the colors and any css as needed.

Other themes I considered were [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy/) and [minimalist](https://github.com/BDHU/minimalist).

I performed a lot of modifications including
- colors
- font families
- enabled font awesome
- reducing font sizes
- snippits on home page instead of full posts
- added featured image to post previews on home page

### Fonts


### Color

I'm a big fan of blue so went with a nice navy shade.
Also made it so headers are a similar color.

Now my css theme looks like this:
```
/* Custom - Blue */
.theme-base-blue .sidebar {
  background-color: #152a59;
}
.theme-base-blue .content a,
.theme-base-blue h1, h2, h3, h4, h5, h6,
.theme-base-blue .related-posts li a:hover {
  color: #184a99;
}
```

## Other Notes
I also had to deal with 301 redirects

Pointing domain name was relatively easy.

## Resources & References
https://github.com/BillRaymond/install-jekyll-apple-silicon/blob/main/README.md
https://github.com/robertmartin8/ReasonableDeviations

## License
Code for the website can be reproduced with attribution and without warranty, under the MIT license.

Content is licensed under the Creative Commons.