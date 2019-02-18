---
layout: post
title:      "Tiny Steps into Data Science"
date:       2019-02-18 18:53:59 +0000
permalink:  tiny_steps_into_data_science
---


Working as a design engineer in a Oil and Gas industry, I did not wake up one day and decided it's time to get into data science. It all started from tiny steps when I was working more and more with data.

"What data?" one may ask, and I'm glad to show you more. With many of our design and geometry getting more and more complex, we start moving away from just typical hand calculation to finite elemental software (FEA) like ANSYS. Often we get result such as below where you see models are divided into mesh for calculations. Each of the colored cells in the web looking mesh are known as elements.

![](https://www.google.com/search?q=fea+ansys+results&rlz=1C1GCEA_enUS833US833&source=lnms&tbm=isch&sa=X&ved=0ahUKEwilwsfO8MXgAhXKzlkKHXfXDE0Q_AUIDigB&biw=1440&bih=781

With finite elemental analysis, we get to experiment with many unconvetional geometry as long as our design structure are sound, often based on critical load paths and support. As things are getting leaner, lighter and stronger, optimization becomes the main topic. This is often done by multiple iterations of the product and it's features to get the final ideal geometry.

A typical process when running itterations is to export elememts of critical points (data) into "database program" such as Excel. O yes, laught at me, but this is SQL and R stuff isn't that popular yet at work place. It was a manageable size data of 5000 points along with noise that we have to filter. Initial combing through them mannually is taxing but still humanly possible. But now, let's optimize it by running 50 iterations. Thank goodness we have functions, logic statements and graphs to help us. It is still workable!

The more I work through the data, the more I realized, this is not just normal designing I am dealling with, but Data Science. How can I train my model to filter noises? Are there trends in a good data or design that we can exploit? Outside of design, how about root cause failure data, predictive maintenance data. As data servers are getting more economic, how can we use these data better?
