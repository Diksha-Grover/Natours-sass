## Sass project

Here I have used scss syntax instead of sass.

-> sass syntax and scss syntax

sass syntax does not contain curly braces and semi-colon
whereas scss syntax does contain them.

eg. sass syntax

.navigation
list-style: none
float: left

    scss syntax

.navigation {
list-style: none
float: left
}

-> for basics of sass
https://codepen.io/thedikshagrover/pen/mdpEEPK?editors=1100

commands used:

-> npm install live-server -g
to install live-server package globally

-> live-server
this command will detect changes that happened in our project

-> npm init
to add package.json file

-> npm install node-sass --save-dev
it will add all the dependencies and node-sass is a tool to develop our project

-> npm run compile:sass
in package.json file:
"compile:sass": "node-sass sass/main.scss css/style.comp.css",

- sass/main.scss this file is the input file which has scss and we wanna convert it into css

- css/style.comp.css file is the output file where we want the converted css

-> npm install concat --save-dev

-> npm run concat:css

-> npm install autoprefixer --save-dev

-> to make the autoprefixer to work
npm install postcss-cli --save-dev

-> npm run prefix:css

-> npm run compress:css

-> npm-run-all --save-dev

-> npm run build:css

New Things learnt by this udemy course:

1. navigation
2. popup
3. 7-1 pattern
4. BEM
5. live-server command
   and many more small concepts
6. how to calculate vw, w and max-width(max-width in em)
   video 62(responsive images of HTML- density resolution switching) of udemy course

===============================================================

Build process

<img src="img/build-process.jpg">
<br>
normally we compile the code while we write the code.<br>
1. So in first step we compile the main.sass file to css file to style.comp.css<br>
2. Then we concatenate the compiled style.comp.css file and the css file to style.concat.css<br>
with having one file we have to generate only one HTTP requeat <br>  
3. Then the file for th prefixes are added which is style.prefix.css<br> 
prefixes like -webkit- <br>
4. At last step entire code is compressed to style.css
<br>
Breakout-points
<br>
<img src="img/breakoutpoints.jpg">
<br>
Responsive-image
<br>
<img src="img/responsive-image.jpg">
<br>
==========================================================

for flexbox

https://codepen.io/thedikshagrover/pen/JjMORqQ?editors=1100