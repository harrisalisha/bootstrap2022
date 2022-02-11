 package copyfiles is  to copy file and create new file called dist
 package rimraf will clean or remove dist folder
 package imagemin is minify image from img folder n will be copy in dist/img
 imagemin img/* --out-dir='dist/img 

 Preparing the Distribution Folder
 in gitignore node_modules dist
 install --save-dev usemin-cli@0.5.1 cssmin@0.4.3 uglifyjs@2.4.11 htmlmin@0.0.7 to use usemin-cli
 <!-- build:css css/main.css --><!-- endbuild -->
 <!-- build:js js/main.js --><!-- endbuild -->
 then npm run build