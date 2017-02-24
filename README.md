# JSON Tech Assessment

### Brief
At 16:30 on 20/02/2017 I was provided with a JSON data file containing content. I was required to create a flat HTML apge with the requisite CSS and Javascript.

### Instructions
- `$ git clone git@github.com:mikehurl/crew-tech-assessment.git`

- `cd crew-tech-assessment`

- `open ./index.html`


### Approach
I did not have access to a laptop until 22/02/2017. I initially decided that due to having less time than given I would create a simple index.html file that could be dragged to the browser to open.

After making this decision, I spent some time researching JSON as I had very limited experience previously.  After a day I had not made a lot of progress. My understanding is that Chrome does not allow the browser to access certain local files.

Further research led me to the idea that I may be best served using Node and Express. Again, having not had much experience with Node and none with Express or Jade/Pug, I spent some time researching and following tutorials. I was able to access the JSON data in the developer console but could not render on the browser even using Browserify (again, an entirely new tool for me).

Due to a quickly approaching deadline, I took the decision to export the JSON data manually into the index.html file. This allowed me to finally complete the task. It is not perfect by any stretch but it can be seen as a minimum viable product.

I utilised the tutorial at https://www.taniarascia.com/how-to-build-a-responsive-image-gallery-with-flexbox/ to deal with the images on my page.

For the Javascript animating, I used code from https://www.w3schools.com/w3css/tryit.asp?filename=tryw3css_slideshow_rr and https://www.w3schools.com/howto/howto_js_slideshow.asp and http://jsfiddle.net/cCvtL/1/

### Future development
I would be keen to determine why the two images associated with each individual coach tip seem to have an additional blank image. This is currently resulting in the two correct images transitioning quickly but then no image is rendered for some time.
