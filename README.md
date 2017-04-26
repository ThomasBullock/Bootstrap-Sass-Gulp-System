# Bootstrap 3 Sass Gulp Build System #
Starter Template For Bootstrap Sass


## Notes

Download and run NPM install.

Custom styles and scripts are concatenated with bootstraps css and js so there is only one styles.css file and one app.js file

###npm run server###
local server on port 8888
###gulp watchFiles###
compiles Sass with autoprefixer and concatenates js scripts
###gulp build###
compiles Sass with autoprefixer and minifies css - concatenates transpiles from es6 and minifies js and outputs project 
to dist folder

## Folder Structure

```
Bootstrap-Sass-Gulp-System/
    README.md
    .babelrc
    gulpfile.js
    package.json
    css/
      styles.css
      styles.css.map
    js/
      app.js
      app.js.map
    node_modules/
      bootstrap-sass/
        assets/
    src/
      javascript/
        main.js
      sass/
        0-plugins/
        1-base/
          mixins/
        2-modules/
        3-layouts/
        styles.scss
    index.html
  
```

