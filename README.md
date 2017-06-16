# Page Performance
Excercise to make the page load faster

**checked through the lighthouse extension provided on chrome**

## Work that has been done

* Optimised the JS. Added async and moved the script tags to the end of the page. 
* Inlined the css in the head of the page when the size was small
* Made the images smaller and added seperate thumbnail images where required
* Changed the link of the font directly to the google api cdn

Current speed score 100

## work still to be done

* Minify HTML, CSS, JS
* Seperate the mobile css to ensure even smaller loading.
* Remove uneccesary classes from the grid css. Use UnCSS in grunt [Addy Osmani Github] (https://github.com/addyosmani/grunt-uncss)

