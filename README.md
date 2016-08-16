# darrenwdunne.github.io.src

This is the source repository for the personal web page at dwdunne.com

Web site initialized with Yeoman to get the environment established. Real-time builds are via Gulp to concat, uglify, etc... to improve runtime performance, and Sass is used to auto-generate the CSS.  

I found Gulp to be much nicer than Grunt, and the Yeoman environment automatically setup the best-of-breed file structure and build environment.

Bootstrap is used to provide the Responsive Web Design. Check it out on a phone or tablet (especially the Projects page)
to see the layout in action.


## To Build

```
git clone ...
npm install
bower install
gulp && gulp serve
```

## To Deploy
```
gulp deploy
```
Note: this will run a build and automatically push the resulting dist directory to
https://github.com/darrenwdunne/darrenwdunne.github.io  

The result is that darrenwdunne.github.io only shows the built files. No source is stored there.
