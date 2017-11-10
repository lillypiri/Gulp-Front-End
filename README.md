#### Project 8

## Gulp 🍹

###### This is the eighth of twelve projects for the 🏡 Treehouse Techdegree Full Stack JavaScript.

This project uses [gulp](https://gulpjs.com/) to set up and prepare a front end website for deployment.

`npm install` to install dependencies.


##### Commands 

`gulp build` command properly runs the `clean`, `scripts`, `styles`, and `images` tasks.

`gulp images` command copies the optimized images to the `dist/content`.

`clean` task fully completes before the `scripts`, `styles`, and `images` tasks are ran.

`gulp scripts` command generates JavaScript source maps.

`gulp styles` command compiles the project’s SCSS files into CSS, and concatenates and minifies into an `all.min.css` file in `dist/styles`.

`gulp styles` command generates CSS source maps.

`gulp` command properly runs the `build` task as a dependency.

`gulp` command serves the project using a local webserver

`gulp clean` command deletes all of the files and folders in the `dist` folder.


Exceeds expectations:

The `gulp` command also listens for changes to any `.scss` file. When there is a change to any `.scss` file, the `gulp styles` command is run, the files are compiled, concatenated and minified to the dist folder, and the browser reloads, displaying the changes