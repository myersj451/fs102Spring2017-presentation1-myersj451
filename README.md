# fs102Spring2017-presentation1-myersj451

This repository contains the HTML source code and additional resources for a presentation on false news found on Google's interface. The presentation's source code uses the
[reveal.js](https://github.com/hakimel/reveal.js/) framework to control the display of each slide. The presentation uses gkapfham/seke2015-panel-presentation as a starting template, but each slide is customized to pertain to issued topic. 

Are you interested in previewing the presentation without having to download the code and resources from the GitHub
site? Well, you can! Please view [Is Big Data a Big Deal? Not Without Correct
Software!](http://cdn.rawgit.com/gkapfham/seke2015-panel-presentation/master/seke2015_panel.html).

## Installation Instructions

Please note that the presentation uses local fonts so that it can be displayed at a conference on a laptop that either
may not have access to the Internet or may only have unreliable Internet access. Some browsers may disallow the loading
of local fonts due to security reasons. However, it should be possible for you to view the presentation correctly when
using Chrome or Chromium on the Ubuntu operating system &mdash; this is my primary development environment and the one
that I used to give the presentation. However, I anticipate that the presentation slides should display correctly on a
wide variety of operating systems and browsers.

I have found that some versions of Chrome and Chromium do not quickly load the full-screen images that I use as
backgrounds. If you notice this problem as well, then I would encourage you to "serve" the presentation with a local Web
server, such as the Ruby-based one available at [jlong/serve](https://github.com/jlong/serve). If you adopt this
approach, then you should type the following command:

```shell
serve 4100
```

Now, you can navigate to the Web site `http://localhost:4100/seke2015_panel.html` and view the presentation. Please raise any issue found in the presentation and/or code. 
