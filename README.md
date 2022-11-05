# steveripplinger.com
This is my website repo for https://www.steveripplinger.com


## Intro
I wanted to recreate my personal website and decided to do it with Jekyll and Github pages. 

I went into this project with no prior knowledge of Ruby/Jekyll and very limited experience with css.

The end result is a lovely code-first approach to a website where I have full control from my VS Code interface, edit writing in markdown, and publish using git.

## Setup
I mostly followed [this guide](https://www.youtube.com/watch?v=UKB9ylw0G4U) to setup Ruby and Jekyll on my mac. [This guide](https://www.youtube.com/watch?v=EmSrQCDsMv4) also helped. [This repo](https://github.com/robertmartin8/ReasonableDeviations) also had some good additional modifications that I incorporated and where I got some inspiration.

## Theme & Design
I decided on [Hyde](https://github.com/poole/hyde) as a nice, two-column theme to start from. It is simple and I can customize and build what I want on top of it.

![Hyde screenshot](https://f.cloud.github.com/assets/98681/1831228/42af6c6a-7384-11e3-98fb-e0b923ee0468.png)

Other themes I considered were [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy/) and [minimalist](https://github.com/BDHU/minimalist).

The basic Hyde theme was a good place to start, but it needed a lot of modification to get to my desired result.

### Color
I'm a big fan of blue so went with a nice navy shade. The sidebar looked a little plain so I added a diagonal gradient with a nice effect when dark-mode toggled.

### Fonts
Fonts say a lot about a person so wanted to be deliberate about my choices here.

The current version is 
- Playfiar Display for main sidebar headings
- SF Compact Display for titles & post-meta
- Roboto for main text

Not quite perfect but is pretty close to what I wanted.

## Added Features & Modifications
I performed a lot of modifications including:
- changing theme colors, font colors, link colors
- added dark mode. This was the most effort but worth it. Takes OS preference plus a toggle with persistance. [This repo](https://github.com/derekkedziora/) was the biggest help to get started.
- optimized website for mobile, since this theme is quite old the sizing didn't translate well to mobile.
  - optimized font sizes for web and mobile
  - made images responsive to sizing for web and mobile
- snippits on home page instead of full posts
- added featured image to post previews on home page (though toggled off)
- added button via javascript to scroll [back to top](https://github.com/vfeskov/vanilla-back-to-top) for posts
- enabled font awesome for icons
- I also had to deal with 301 redirects with this [solution](https://github.com/jekyll/jekyll-redirect-from).

## Resources & References
setup - https://github.com/BillRaymond/install-jekyll-apple-silicon/blob/main/README.md  
theme - https://github.com/poole/hyde  
ideas and some modifications - https://github.com/robertmartin8/ReasonableDeviations  
back-to-top javascript - https://github.com/vfeskov/vanilla-back-to-top  
301 redirects - https://github.com/jekyll/jekyll-redirect-from  
dark mode - https://github.com/derekkedziora/


## License
Code for the website can be reproduced with attribution and without warranty, under the MIT license.

Content is copyright per <a href="/disclaimer">Disclaimer.</a>
