---
layout: post
title: HTML presentation frameworks
tags: 
  - presentations
---

There are loads of HTML5/CSS/JavaScript presentation frameworks out there. I had seen a couple of these in action and was kind of impressed. While [Keynote](http://www.macuser.com/people/keynote_er_al_gore_wins_nobel.php) is not as bad as [PowerPoint](http://www.wired.com/wired/archive/11.09/ppt2.html), they both force you to think about design and content simultaneously. Because the design and layout is right in front of you, it can be hard to focus just on content, and I often find myself tweaking design when I should be thinking about content. So that led me to think, hey, wouldnt it be great if I could create my presentations with [markdown](http://daringfireball.net/projects/markdown/) or something similar?

Here are the presentation frameworks I found and took a look at, in order of github stars:

* **impress.js** ([github](https://github.com/bartaz/impress.js/) / [demo](http://bartaz.github.com/impress.js/)) is essentially a clone of [prezi](http://prezi.com/), allowing for really crazy presentations that use all sorts of transformations on an infinite canvas. This isnt the kind of thing I was looking for, but it does live up to its name (in the same way that the first time you see a 3D globe does). Documentation seems to be lacking, but it seems very popular (~13,000 stars).

* **reveal.js** ([github](https://github.com/hakimel/reveal.js) / [demo](http://lab.hakim.se/reveal-js/#/)) includes  nested slides, markdown contents, PDF export (using Chrome via a special style sheet), and speaker notes. Content can be created in html or *markdown* (yay), and there is even an online editor, [rvl.io](http://www.rvl.io/). Navigation by keyboard or touch events (swipe) or an overview hotkey that zooms you out (press ESC). There are lots of different transitions and default themes. Code highlighting is included by way of [highlight.js](http://softwaremaniacs.org/soft/highlight/en/description/).

* **[deck.js](http://imakewebthings.com/deck.js/)** ([github](https://github.com/imakewebthings/deck.js) / [demo](http://imakewebthings.com/deck.js/introduction/)) seems mature and has a whole ecosystem around it. Content is created in HTML. Navigation by keyboard or touch events (swipe) or an overview hotkey (or touch double tap). Deck.js supports extensions, and beyond the default ones, there appears to be a whole bunch of contributed ones on the [project wiki](https://github.com/imakewebthings/deck.js/wiki), including lots of options for writing content in [Jade](http://jade-lang.com/) or markdown.

* **flowtime.js** ([github](https://github.com/marcolago/flowtime.js) / [demo](http://flowtime-js.marcolago.com/)) is a relative newcomer, but seems pretty nice. Content is created in HTML. Navigation by keyboard or touch events or clicking on the overview. The one thing that sets flowtime apart is the overview, which displays all slides in a grid. The flowtime.js demo crashed both Chrome and Safari on my iPad, so not sure if mobile is really an option.

* **[fathom.js](http://markdalgleish.com/projects/fathom/)** ([github](http://github.com/markdalgleish/fathom) / [demo]()) is a jquery plugin that is limited in terms of features, but looks easy to get started with. Content is created in HTML. Navigation by keyboard or mouse. The demo is a bit awkward on an iPad, you can scroll but it is more like scrolling a web page than flipping through slides. You can sync the video of your presentation, although that wasnt important for me. 

The ability of reveal.js to export to PDF and write slides in markdown are two features that set it apart. The export to PDF feature seems to only be available in reveal.js; I would like to see more support for that as there are times when I can only bring a pdf or ppt file to a presentation. Deck.js also seems solid, especially when all of the contributed plugins are considered. 