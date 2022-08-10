# landing-page

Landing Page for my awesome cat Nar-nar, completed as an assignment for The Odin Project (TOP).

## Process

### > Basic Sections

Most of the website is built using flex elements, which makes sense as this section of TOP involved learning flex elements. 

I had to research a lot to make this website. The first obstacle with creating the basic elements was using flex properly while maintaining fluid design. The website looked great on a large device but broke down on mobile. Despite the assignment specifying no need for responsive design, I wanted to push myself until I did it. I eventually found the answer by using vw units instead of px, as well as media queries. I am really happy with how this turned out.

The weirdest bug I encountered had to do with descender elements in fonts and resulted in a 3.5px margin under one of the elements. This bug was incredibly frustrating, but I eventually found the [solution](https://stackoverflow.com/questions/19212352/div-height-based-on-child-image-height-adds-few-extra-pixels-at-the-bottom) which I found fascinating.

### > Space Section

I wanted to have a visual section half way through the site which used css animations. This was completely separate from the curriculum but I stubbornly spent days on it until I figured it out.

I found a parallax background example written in haml and sass which I wasn't familiar with. I converted the haml to html using a web tool, but I had to rewrite the sass into scss before I could use it in my project. I learned a lot about both from this process. After this, I had to make many modifications as far and near stars were moving at the wrong speeds for the effect to be convincing. I also changed the direction of the stars as I envisioned a spaceship traveling through it horizontally, and added different blur amounts to the star layers until I was happy with the result. 

I added an image I created in Gimp and also added a pure css fire effect. This was also challenging as it used pug instead of html which I wasn't familiar with, but I found a way to rewrite it into html. The main challenge with this effect is learning how to change the size and direction of the flames, and how to align it. This took me days of trial and error before I solved the problem with variables and math. I added some blur and contrast to the effect which made it look fantastic, and sped it up to mimic a rocket thruster.

### > Compatibility

This webpage was built to be compatible on Firefox and Chrome.

## Credits

This project wouldn't be possible without open source contributions by the below artists and coders:

Model - Nar-Nar the cat

Rocket Stock Image - [Chichou](https://pixabay.com/users/chichou-25174741/)

Star background remixed from source code by [sarazond](https://codepen.io/sarazond) - [Parallax Star Background in CSS](https://codepen.io/sarazond/pen/LYGbwj)

Rocket thrust remixed from source code by [jkantner](https://codepen.io/jkantner) - [CSS Blend Mode Fire](https://codepen.io/jkantner/pen/gKRKKb)