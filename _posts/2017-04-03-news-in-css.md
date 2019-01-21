---
layout: post
title: New features in CSS or features you have missed
published: true
---

CSS is still evoluting.

* CSS 2 to CSS 3
* From css to preprocessors
* Post processor
* CSS 4

Also the number of possibilities in css is high. And probably as me, you have missed some handy or cool stuff css3 or more have brought to css.

### Boostrap 4 

<img src="./boostrap-flexbox.png" alt="new featurs in boostrap 4" />

* [What changes in v4 version](https://hackernoon.com/what-changed-in-bootstrap-4-0-ca3cbbf4f62f)
    * sass
    * grid with flexbox (allow vertical alignement)
    * grid unit less columns
    * rem font sizing 
    * new small screen breakpoints  

### CSS Grid 

* Learn  grid  with [grid garden](http://cssgridgarden.com/) learning game

* use of css grid in production right now ? https://www.smashingmagazine.com/2017/06/building-production-ready-css-grid-layout

* another tutorial on css grid https://hacks.mozilla.org/2017/10/an-introduction-to-css-grid-layout-part-1/
### Flexbox

Learn flexbox with [flexbox froggy](http://flexboxfroggy.com/) learning game

### CSS counter 

When you have a list of item and use a `content` tag to define content with css. And what if you want to add to this content the number of item in a list without changing the js. 

The [css counter](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Lists_and_Counters/Using_CSS_counters) are exactly for that.

### **transition**

* **Understand transition**

[Nice visualisation to choose a transition timing function or design custom bezier function](http://www.the-art-of-web.com/css/timing-function/)

* **Cubic bezier generator**

[http://cubic-bezier.com/#.95,.23,.83,.67](http://cubic-bezier.com/#.95,.23,.83,.67)

<img src="../images/css-cubic-bezier.png" title="cubic bezier generator">

### **object fit**

Object fit allow to simulate cover property of background images
It is good to make framing of an image or video inside an object...


[The IA Fall back](https://medium.com/@primozcigler/neat-trick-for-css-object-fit-fallback-on-edge-and-other-browsers-afbc53bbb2c3)

### **blend modes**

Blend mode are photoshop like fusion mode (multiply, transfer...) that allow to have an opacity without flattening everything

[https://medium.com/@bennettfeely/css-blend-modes-could-be-the-next-big-thing-in-web-design-6b51bf53743a](https://medium.com/@bennettfeely/css-blend-modes-could-be-the-next-big-thing-in-web-design-6b51bf53743a)

More in depth tuto
[https://css-tricks.com/basics-css-blend-modes/](https://css-tricks.com/basics-css-blend-modes/)

<a href="http://bennettfeely.com/gradients/">
  <img src="../images/css-blend-mode.png" title="examples of mix blend mode">
</a>


Example for a video with a gradient with mix-blend-mode

[Original tuto](http://thenewcode.com/1020/HTML5-Video-Effects-with-CSS-Blend-Modes)

The html :
```html
<figure>
	<video>
		<source src="lina.webm">
		<source src="lina.mp4">
	</video>
</figure>
```

The CSS :
```css
figure {
	background: linear-gradient(90deg,#00f 50%,transparent 50.1%);
}
figure video {
  /* Mind we use mix-blend-mode as video is a normal html element
  not a background */
  mix-blend-mode: overlay;
}
```

* Example with letter overlap

[http://codepen.io/chriscoyier/pen/mvbpJ](http://codepen.io/chriscoyier/pen/mvbpJ)

### **Viemport units vh vw**

Allow to size depending of the screen size, ideal for full width

[http://www.tipue.com/blog/css3-vw-vh](http://www.tipue.com/blog/css3-vw-vh/)


### **always and ever a problem : vertical align**

Flexbox based solutions

### position sticky 

* (Can I use Sticky)[https://caniuse.com/#feat=css-sticky]
* Sticky Bits https://css-tricks.com/stickybits-alternative-position-sticky-polyfills/
* More in depth article to understand position sticky [https://www.sitepoint.com/css-position-sticky-introduction-polyfills/](https://www.sitepoint.com/css-position-sticky-introduction-polyfills/)
End of [2017 support](https://caniuse.com/#feat=css-sticky) for position sticky: supported by all expept IE.

Classical solutions :

[http://vanseodesign.com/css/vertical-centering/](http://vanseodesign.com/css/vertical-centering/)

### **Post css**

* Introduction post about [post css](http://julian.io/some-things-you-may-think-about-postcss-and-you-might-be-wrong/)
https://github.com/MoOx/postcss-cssnext)

* **post css parts** The module platform for post css

* **post css / css next**

Plugin to use future of css now (a bit the equivalent of babel and typescript for the css)

[https://github.com/MoOx/postcss-cssnext](https://github.com/MoOx/postcss-cssnext)

* **post css / Autoprefixer**

Set automatically browser prefix for you

[https://github.com/postcss/autoprefixer](https://github.com/postcss/autoprefixer)

* **post css web pack plugin**

[https://github.com/postcss/postcss-loader](https://github.com/postcss/postcss-loader)

* **Flexbox nice tutorial**

[http://cssreference.io/flexbox/](http://cssreference.io/flexbox/)


### SCSS / SASS

* SASS MAPS 

[http://clubmate.fi/sass-maps-syntax-examples-and-good-things/](http://clubmate.fi/sass-maps-syntax-examples-and-good-things/)
