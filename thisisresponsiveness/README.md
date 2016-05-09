#This is Responsiveness

This is the third of three exercises introducing you to the basics of static web programming (i.e. front-end programming, sans Javascript). We'll learn how to integrate responsive principles into our CSS rules, to allow our layouts to adapt to the user's device.

You'll learn how to create fluid, responsive layouts that look good at all widths, and are future-proof!

###Prerequisites
* You've completed [This is HTML5](https://github.com/launchcode-rebootu/thisisthemodernweb/tree/gh-pages/thisiscss3)
* You understand the primary CSS units: px, em, %. ([w3schools CSS Units Reference](http://www.w3schools.com/cssref/css_units.asp))

###Your mission, should you choose to accept it:
1. Give your page a flexible layout, that is, one based on percentage widths rather than pixel widths.
2. Make sure your font sizes are all specified in `em`'s. You may have already done this in the last exercise, when it was as suggestions, but now it's a requirement.
3. Make sure any other pixel measurements in your stylesheet are replaced with `em` measurements. Why? Read ["Why Ems?"](https://css-tricks.com/why-ems/).
4. Make your images fluid by setting `img { max-width: 100%; }` in your stylesheet. Congratulations! You've just created a fluid (or liquid) layout.
5. Determine which breakpoints you need. If you have a single-column layout, you may only need minor breakpoints, where you adjust font size, margin and padding. Start with a narrow width, and move outward as you adjust, using mobile-first princicples.
6. When you're done, submit a pull request to the main repo.

###Testing

To test your layout, combine each of the following techniques, as needed:
* Resize your browser, looking for any width ranges for which the content doesn't look good. Firefox's Web Developer Toolbar can be helpful in determining browser width, when you notice such a range (Resize > Display Browser Width).
* View your site at some specific widths, using Resize > View Responsive Layouts in Firefox's Web Developer Toolbar, or by visiting a site such as [responsinator.com](http://www.responsinator.com). However, be sure to test your layout at ranges of widths, not just at fixed, specific widths based on current devices.

###Resources

* [Which Layout? Static, Liquid, Adaptive, or Responsive](http://blog.teamtreehouse.com/which-page-layout)
* [w3schools Media Queries Reference](http://www.w3schools.com/cssref/css3_pr_mediaquery.asp)
* [How to Choose Breakpoints](https://developers.google.com/web/fundamentals/layouts/rwd-fundamentals/how-to-choose-breakpoints?hl=en)
