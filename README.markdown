# CSS Image Maps

A friend was asking me how to do a simple image map using HTML and I
realized it had been years since I had used any of those. It felt wrong
to even consider putting such markup inside an HTML document so I wiped
up a quick example using extremely simple HTML5 markup and CSS.

You could use classes to target the list items but why bother when the
:nth-child selector is so handy. Likewise, I could have simply put a
series of anchor elements in the div but semantically this is a list of
links to sections of a site, they should be nested inside of an
unordered list.

## Compatibility

I have not cross-browser proofed the CSS stylesheet since I only tested
within Chrome so if you wish to use this code in production I recommend 
Paul Irish & Jonathan Neal's excellent [CSS3 Please](http://css3please.com/).
