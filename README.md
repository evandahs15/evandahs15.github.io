<strong> My Workflow with Gulp JS </strong> <br>
I am using gulp.js to automate all my tasks - This included minimising image file sizes for optimisation, compiling SASS files into one CSS, compiling multiple Javascript files into one JS file, using browsersync to listen on port3000, and to deploy all final work to the master branch where GITHUB Pages is hosting my website on a custom domain name.

<strong>Source Folder</strong><br>
This contains all files to produce my website. I am using gulp as an automated taskrunner, and to compile and minimise all my SASS, JS, and image files into the build Folder.<br>

<strong> Build Folder </strong> <br>
Once everything is compiled into the build folder, gulp then serves the files to the browser on port3000 using browserSync.

<strong> Publish Folder </strong> <br>
When you run Gulp deploy on the command line, the build folder will be compiled again into the Publish Folder to be deployed onto the master branchwhere GITHUB Pages is hosting my website on a custom domain name.
