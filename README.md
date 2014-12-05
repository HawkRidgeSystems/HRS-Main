Hawk Ridge Systems - Main Website
========
Hawk Ridge Systems is the leading SOLIDWORKS reseller for 3D design software, analysis software, product data management software, and technical communication software.

About
----
This is a repo for the Main HRS site, this does not include the blog, store, or hawkware apps site. This is solely the main site.

**Technologies used**
  1. ExpressionEngine
  2. Stash Plugin
  3. Bootstrap 3
  4. SASS

1 - Expression Engine
---

[ExpressionEngine](https://ellislab.com/expressionengine/) templates are committed here so they have proper documentation on their development. Templates on the live site aren't updated through the EE templating engine, rather they're worked on a local EE installation, committed to github, and pulled into the live site.

2 - Stash Plugin
---

[Stash](https://github.com/croxton/Stash) was a major theme development in trying to condense and streamline all of our current templates. Making it faster and easier to understand, thus moving our development into a Stash methodology was crucial. 

3 - Bootstrap 3
---

[Bootstrap 3](http://getbootstrap.com) is our major framework that drives and controls our designs and mobile architechture. Very useful in our current setup, used alongside jquery and fontawesome. 

4 - SASS
---

[SASS](sass-lang.com) is a CSS preprocessor that we use to better control our CSS. We have a lot of working parts throughout the site and it's hard to keep track of everything. So using SASS that is preprocessed using LiveReload is a better method for clean and useful CSS. Also, it's easier to pick and choose which parts are useful for our minisites. For further details on how I used SASS with EE see [here](http://www.jhonparedes.com/2014/12/02/SASS_and_EE/)
