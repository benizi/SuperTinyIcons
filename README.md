# Super Tiny Social Icons
Under 1KB each! Super Tiny Social Icons are minuscule SVG versions of your favourite logos

The logos have a 512x512 viewbox and will scale up and down to suit your needs.

Originally created for my contact page - https://edent.tel/

## How Small?

| 839 Bytes SVG	| 18,580 Bytes PNG	|   436 Bytes SVG	| 16,019 Bytes PNG	|  275 Bytes SVG	| 13,485 Bytes PNG	|
|------	        |-----------     	|------	            |----------	        |------	        |-----------	        |
| <img src="https://cdn.rawgit.com/edent/SuperTinySocialIcons/master/tiny/github.svg" width="100" />  	| <img src="https://cdn.rawgit.com/edent/SuperTinySocialIcons/master/original/github.png" width="100" />        	| <img src="https://cdn.rawgit.com/edent/SuperTinySocialIcons/1d6887058425cbfe913ed0abcf4480c449212008/tiny/twitter.svg" width="100" />   	| <img src="https://cdn.rawgit.com/edent/SuperTinySocialIcons/master/original/twitter.png" width="100" />       	| <img src="https://cdn.rawgit.com/edent/SuperTinySocialIcons/master/tiny/flickr.svg" width="100" />   	| <img src="https://cdn.rawgit.com/edent/SuperTinySocialIcons/master/original/flickr.png" width="100" />       	|

## Why so smallious?

Bytes cost money.  They cost money to store, transport, and process.  Simplicity should be our goal in all endeavours.

## Can you go smaller?

Yes! These files were minified using [svgo](https://github.com/svg/svgo) and then hand edited.  Further smallification is possible.

* Each of these has an `xmlns="http://www.w3.org/2000/svg"` in the `<svg>` tag. This isn't strictly necessary - but some web browsers won't display them as an image without it.
* Newlines can be stripped - they've been kept for readability where possible.
* Rounded corners can be dropped - `rx="15%" ry="15%"` - the effect can be done in CSV if you want.
* The background colour can also be excluded if you're including it elsewhere.
* Colours can be simplified. `#FF0000` becomes `red`
* The precision of the paths is *mostly* 0 decimal places. A few logos have 1 or 2 dp to make them look more accurate. The precision can be reduced if necessary.

You can see the difference this makes in `youtube.svg` which is a ginormous 1,074 Bytes. By applyig some of the above techniques we can get it down to a svelte 998 Bytes in `youtube-tiny.svg`.

Think you can make them smaller? Tell me by raising an issue!

Want more icons?  Tell me by raising an issue!

## Licenses

The majority of these vector logos are based on someone else's work.

* [Social Media Icons by Aha-Soft](https://www.iconfinder.com/iconsets/social-flat-rounded-rects) - CC-BY
* [Phone Icon](https://www.iconfinder.com/icons/1807538/phone_icon#size=128) - Free
* [Lock Icon](https://www.iconfinder.com/icons/1814107/lock_padlock_secure_icon#size=512) - MIT
* [Wire Logo](https://commons.wikimedia.org/wiki/File:Wire_software_logo.svg) - Public Domain
* [Signal Logo](https://github.com/WhisperSystems/Signal-iOS/blob/master/Signal/Images.xcassets/logoSignal.imageset/logoSignal.pdf) - GPLv3
* [HTML5 Shield](https://www.w3.org/html/logo/) - CC-BY

Where possible, they retain their original licenses.  Some logos may be subject to copyright laws, but these files are small enough to memorise.
