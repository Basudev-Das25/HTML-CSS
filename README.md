# HTML-CSS

Learning HTML and CSS
#study material from w3school and mdn-web-docs
#youtube channel --- HuXn WebDev ---

Html: 1. formatting 2. typography 3. Semantic 4. Tags 5. Links and hyperlinks

CSS: 1. Styling 2. Cascading Style Sheets 3. inline,internal,external CSS 4. Colors-Names,rgb,rgba,hex 5. Font- em-related to the current font size of the html doc, rem- it relative em 6. vw and vh for view port height and width uses percentage of the cuurent viewport

Typography: it is all about font and its styling. 1. font-family-the font style that the browser will show(default-Serif). 2. ctrl+space for all local font family and can also be done via google font. 3. font size- declaring the size of the font you are using. 4. text-transform: used for phorming of the text such as transforming in lowercase, uppercase, capitalize. 5. Line-height: declaring the space between the lines. 6. letter-spacing: space between the letters. 7. word-spacing: space between words. 8. text-align- alignment of the text.

Section Formating: 1. Content 2. padding 3. border 4. margin

Properties: 1. Background-color: color of the background. 2. background-image: image is provided as the background. 3. background-repeat: to repeat the image bound to axis or no-repeat. 4. background-size: eg. cover. 5. background-position: to position the image to the desired areas. 6. background-attachment: can be given to show effect of view to image background whi.,e scrolling.

Gradient and filters: 1. linear-gradient 2. radial-gradient 3. filter as the name suggest is used to apply a filter or a layer on top of the image or background or in genral view for applying certain effects as required.eg- grayscale, saturation, brightness, blur.

Cools areas to find gradient for projects such as- grabient.com and webgradient.com

Advance Selectors: 1. They are multiple ways a item can be selected in CSS through ways such as class selector, id selector, psedu-selector and as such. 2. '.'--class 3. '#' --id 4. '<element>' --element 5. '<element> <element>' div p --all p inside div. 6. '<element1>><element2>' div>p --all p where parent is div. 7. '<element>+<element>' div+p --first p immediately after div. 8. '<element>~<element>' p~ul --ul preceeded by p etc. 9. '[attribute]' --attribute selector. 10. psedu-selectors:{ 1. link: effective for the link before visiting. 2. visited: effective for the link after visiting. 3. hover: set the effect for hover effect for everything. 4. active: effective when the active interaction is done.
}.

Display: 1. block- it can take height and weight and act as a full block 2. inline- it will not take any height and width value. 3. inline-block - gives the property of both inline and block element.

icon: 1. fontawesome.com- cool svg icon and cdjns.com

shadow: 1. box-shadow 2. text-shadow

CSS inheritance:

1.  typography style is the only thing that is inheritable by the parent to the children.
2.  layout cannot be inherited.

Position: 1. fixed-- fixed to certain part of the viewport. 2. relative 3. sticky-- similar to fixed but is only fixed in certain boundaries. 4. absolute

flexbox: 1. one-dimensinal layout model 2. display type- flex 3. flex-direction
justify-content property is reposible for aligning the items on the main axis. 1. space-around: distribute item along the flex by providing space. 2. space between: space creation between items but remove space for the extreme sides.
flex-wrap: for wrapping the items around.
align-items: it is different from justify content by working on cross axis.

Order: 1. default value of all children will be 0. 2. help to bring order in the items.

align-self: specifies the alignment of items one at a time.
flex-grow: specifies how much the item will grow relative to the rest of the flexible items inside the same character. Also if the element is not flexible item, the flex-grow property has no effect.
flex-basis: specifies the initial length of the flexible item. it also works only on flexible items.
flex-shrink: specifies the how the item will shrink to relative to the rest of flexible item. it also works only on flexible item.

BEST PRACTICE MATERIAL: flexbox froggy on web play the game and complete it.

Grid: 1. works on 2 dimensional layout. 2. Gridline can either be horizontal or vertical used to seperate items in grod. 3. Grid track is the space between 2 grid line. 4. Grid cell are areas sperated by four grid lines. 5. grid area are areas where one or more grid cells make up a rectangular area. 6. autofill, autofit 7. we can use flexbox properties on grid as well such as jsutify-content, align-items etc. 8. Grid-template-area layouting purpose. 9. Grid-area used to declare the name of the area into template.

calc(): it is a built-in function and is used to do calculation in css. 1. width: calc(100px+100px); 2. height: calc(100px-50px);
mix-blend-mode: it sets how the element's content should blend with the content of element's parent and the elements background.
is(): it is a psedu selector. it take a list as argument.
before and after psedu selector. **<very immportant>**
not(): it also a pseudo selector.

Animation: all works on key frames.
@keyframes InAndOut {
0%{
transform: scale(2);
}

25%{
transform: scale(0.2);
background-color: teal;
transform: skew(10deg);
}

#and soo on sii forth....
}

Properties in animation: 1. animation name: name that you have given to the animation. 2. animation duration: the timeduration of your animation. 3. animation iteration count: decalre the number of iteration for the animation. 4. animation timing function.

<!-- media queries very important -->

    @media screen and (<!----condition here----!>){
        <!-- ---Logic here--- -->
    }
