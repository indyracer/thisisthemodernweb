#This is HTML5

This is the first of three exercises, which build off of each other. You'll get comfortable with semantic markup, some elements introduced by HTML5, and separating content from design and layout.

###Prerequisites
* You've set up your environment and the project as outlined in the project README
* Familiarity with the basics of HTML
* Understanding of importance of semantic markup. If the phrase "semantic markup" has you scratching your head, read an [overview](http://shapeshed.com/the_importance_of_semantic_markup/) or [two](http://html5doctor.com/lets-talk-about-semantics/), and bookmark the [HTML5 Doctor Element Index](http://html5doctor.com/element-index/).

###Your mission, should you choose to accept it:

1. Stub out `submissions/<username>/index.html` it out with these basic elements: the HTML5 doctype, `<html>`, `<head>`, `<title>`, and `<body>`, with appropriate content.
2. Add five `<meta>` tags to the `<head>`, one to specify the `charset` as UTF-8, and four with `name`/`content` attribute pairs, with `name` equal to each of `"description"`, `"keywords"`, `"author"` and `"viewport"`. (To brush up on these `<meta>` tags, head over to [w3schools](http://www.w3schools.com/tags/tag_meta.asp) and look at the source for [my page in the project](http://launchcode-rebootu.github.io/thisisthemodernweb/submissions/chrisbay/).) You don't need to fully understand what each of these does; that will become clear as we go along.
3. Build a page that...
	* Tells a story. This can be personal, or not. Funny, serious or neither. You can do whatever you like, but generally, it should be something in the range of 3-10 paragraphs or sections. Here are some ideas:
		- Tell your backstory (a&#768; la [about.me](https://about.me/backstory))
		- Tell the story of a trip that you took
		- Talk about some hobby or passion of yours
	* Does each of the following:
		- Uses each of the following structural HTML5 tags: `<header>`, `<footer>`, `<main>`, `<article>`, `<section>`, `<aside>`, and `<nav>`
		- Use at least one `<img>` tag (and hopefully more). If you find yourself wanting or needing to edit images on the Mac, I recommend installing [GIMP](http://www.gimp.org/downloads/). If you simply need to resize some photos to a common width or height, [try using Automator on the Mac](http://osxdaily.com/2011/12/20/batch-resize-pictures-in-mac-os-x-using-automator/). When placing images in your page, put them in a new directory called `images` within your `<username>` directory.
		- Uses at least on [HTML entity](http://www.w3schools.com/html/html_entities.asp). Hint: putting a copyright notice in your footer will afford you the opportunity to use &copy;, but you should also try to get creative here.
		- Gets creative. Don't stop with these items or tags. Have some ideas for your page, and make it great. And dig into the [w3schools HTML reference](http://www.w3schools.com/tags/default.asp) to learn more about other tags, their usage and attributes!
4. Don't break these rules:
	* No CSS.
	* Really, no CSS!
	* Each HTML5 element should have semantic meaning. If you add a `<div>` or `<span>` you should be ready to justify your decision.
	* Your page must validate as HTML5 using the [w3c Validator](http://validator.w3.org). Among other things, this means you may not use things such as `<font>` or `<b>` tags, or the `background` attribute on your `<body>`. (Don't worry, we'll make our page look pretty later.)
	* Be original, and create your page without looking at the source for other pages in the project (other than the one linked above).
5. When you're done, `git add` new files, then commit and push all changes to your fork (include a useful message with your commit), and [create a pull request](https://help.github.com/articles/creating-a-pull-request/) so your changes can be merged into the main repo. When pushing, not that you need to push to the `gh-pages` branch.
6. Wait for your changes to be pulled, and then look for your page on [the project page](http://launchcode-rebootu.github.io/thisisthemodernweb/)!
7. Well done. Time to [dive into some CSS](https://github.com/launchcode-rebootu/thisisthemodernweb/tree/gh-pages/thisiscss3)!

###Resources

####HTML5 & CSS3 browser support
* [HTML5 elements and usage](http://html5doctor.com/element-index/)
* [Can I Use?](http://caniuse.com)
* [HTML5 Please](http://html5please.com)
* [HTML5 and CSS3 Readiness](http://html5readiness.com)
* [HTML5 Test](https://html5test.com)
* [How to add HTML5 elements to IE versions < 9](http://www.w3schools.com/html/html5_browsers.asp)

####Semantic markup
* [Let's Talk About Semantics](http://html5doctor.com/lets-talk-about-semantics/)
* [Structural element flow chart](http://html5doctor.com/downloads/h5d-sectioning-flowchart.png)

####General
* [The <!DOCTYPE> declaration](http://www.w3schools.com/tags/tag_DOCTYPE.asp)
* [Quirks mode (at Wikipedia)](http://en.wikipedia.org/wiki/Quirks_mode)
* [Quirks mode examples](http://examples.strictquirks.nl/quirks/)
* [HTML5 Spec](http://www.w3.org/TR/html5/) (a good cure for insomnia)
* [w3schools Browser Stats](http://www.w3schools.com/browsers/browsers_stats.asp)
