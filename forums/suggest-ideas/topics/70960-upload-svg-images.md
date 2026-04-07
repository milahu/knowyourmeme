# upload SVG images

https://knowyourmeme.com/forums/suggest-ideas/topics/70960-upload-svg-images

---

milahu

currently i can only upload raster images

actual:  
when i try to upload SVG images  
then the upload form throws the error  
"Image content type is invalid"

why:  
SVG images are better for re-using or printing

examples:  
github.com/milahu/memes-svg

---

Autumn Able
Moderator

The site's code would have no idea how to handle SVGs currently. Also, the site's code hasn't even been updated to handle WebP images, which is kinda bothersome as a lot of sites have switched to using them.

---

milahu

adding SVG support is trivial, with one caveat:  
SVG files can contain javascript, which allows SVG XSS attacks  
so the uploader should reject all SVG files with javascript
