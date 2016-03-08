# Test speed of separate elements for optimisation

# Benchmarking/Testing tools

http://webpagetest.org
http://gtmetrix.com
http://www.giftofspeed.com

# Tip 1 - Reduce number of network request

We do this because any additional request takes communication time between client browser and server, hence increasing the back and forth.

We can reduce by moving some of the smaller images into a spritesheet or inline-css.

*Spritesheet:* Can be done manually or with a software that generates the position of each images.

*Inline-CSS:* Convert the existing image into base64 code that can be included in a CSS file. This is best for small images (eg: less than 50kb)
Image to base64 Converter: http://jpillora.com/base64-encoder/


# Tip 2 - Lazyload images

Only load those images that are viewable by the user. Useful when your page is vertically long.

https://github.com/vladimirkr/angular-img-lazy-load
http://verlok.github.io/lazyload/
https://github.com/Pentiado/angular-lazy-img

# Tip 3 - Optimise images

Images that comes out of photoshop may not be optimised ideally. Use several compression algorithm to reduce the size further. For Mac, you can try imageOptim or similar alternative for Windows.

Mac:
https://imageoptim.com/

Windows:
http://luci.criosweb.ro/riot/
http://pnggauntlet.com

# Tip 4 - Server configuration

etag, cache, expire headers, gzip, keep-alive

# Tip 5 - Minify JS/CSS/HTML

Minify and combine separate files into one


