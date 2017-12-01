# Easy CSS Button Hover Effects
Eye Catching [CSS button hover effects](http://blog.dynamicdrive.com/popular-css-button-hover-effects-explained/) using pseudo elements. Can be used on submit buttons (using `BUTTON type="submit"`) or any container elements.

![Simple CSS Button Hover Effects](css-submit-button-hover-effects.jpg?raw=true "Simple CSS Button Hover Effects")

## Usage ##

Include the .css file in the `HEAD` of your page. Then, create a button or link, and add the class `buttonfx` to create a basic "Slide Down" effect:

    <button class="buttonfx" type="submit">Slide Down</button>

Add one of the following classes in addition to create compounding or totally different effects:

+ `slideleft`
+ `slidebottomleft`
+ `angleinleft`
+ `curtaindown`
+ `curtainup`
+ `angleindouble`
+ `doubletake`

For example:

    <button class="buttonfx slidebottomleft">Slide Corner</button>
  
### Adding a Bounce Effect ###

To add a bounce effect to any of the above effects, add a `bouncein` class:

    <button class="buttonfx slidebottomleft bouncein">Bounce Corner</button>

And that's it!
