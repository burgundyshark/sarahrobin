---
title: "Its 2017, why are you using Float?"
date: 2017-06-04T02:23:07-07:00
draft: true
---
Dear internet still using floats for page layout,

Why not flexbox?

Is it because you’re worried about browser support? [You shouldn’t be](https://caniuse.com/#feat=flexbox). Unless you need to support IE 10 and under (which is the definition of true sadness in 2016), you’re supported!

Is it because you’re using a prefab grid system in a larger framework? Well, both [Bootstrap](https://getbootstrap.com/docs/4.0/utilities/flex/) and [Foundation](https://foundation.zurb.com/sites/docs/flex-grid.html) have moved to flexbox grids instead of float-based ones. In fact, a lot of what flexbox allows you to do is [recreate complex layouts](https://philipwalton.github.io/solved-by-flexbox/) that used to require a framework in just a couple of lines of vanilla CSS!

Is it because its confusing and new and frustrating? That’s understandable ([though I wouldn’t really call flexbox new](https://www.w3.org/TR/2009/WD-css3-flexbox-20090723/)). If so, allow me to share some handy links that will hopefully will help you adopt this powerful, well-supported, sanity-saving set of features that make CSS dramatically less crap.

If you like videos, may I highly recommend Wes Bos’s [What the Flexbox](https://flexbox.io/) series. It’s 20 short (under 10m) videos for learning the ins and outs of flexbox.

If games are more your thing, check out [Flexbox Froggy](http://flexboxfroggy.com/). Play frogger and learn flexbox at the same time! Also, after polling numerous amphibians, I can safely say this is the definitive cutest way to learn flexbox. Looking for more action/explosions/strategy? Try [FlexboxDefense](http://www.flexboxdefense.com/). It’s a tower defense game for learning flexbox!

Interested in more real world applications of Flexbox? Then [Solved By Flexbox](https://philipwalton.github.io/solved-by-flexbox/) is your jam. I linked to it above, but its so dang useful it bears mentioning again. Try just downloading some of the templates and screwing around with them as the basis for a page and I think you’ll be pleasantly surprised by how much you can accomplish with zero framework or grid library.

Rather go the traditional tutorial route? Check out [LearnLayout’s excellent chapter on Flexbox](http://learnlayout.com/flexbox.html). Its a great introduction, but don’t forget to check out the rest of what LearnLayout offers – its a great guide for getting into building web-based UIs.

Looking for a handy reference guide? Look no further than [CSS Tricks’s Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/), a link I have personally visited so many times I’m shocked it isn’t half-burned into my monitor.

Just the facts, ma’am? Well, okay, as per usual, [MDN delivers](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox). If you want flexbox docs, this is the place for it (along with docs for every damn thing about vanilla web technologies).

In conclusion, please, consider using flexbox. You’ll be a happier person for it, your codebase will look prettier, and your time spent navigating the hazards of abusing float for layout purposes will shrink to dang near zero.