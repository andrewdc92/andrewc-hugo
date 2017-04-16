+++
categories = []
date = "2017-04-16T16:29:40-07:00"
tags = []
title = "my_experience_with_netlify"

+++
Overall I had a positive experience, but I can definitely outline a few points of confusion.

I'd imagine that my experience falls into a common use case, in that the user builds the site before selecting their means of deployment. Now, even though I knew I'd be using Netlify, I followed Hugo's documentation first, and was able to get a nice looking site on localhost. However, the variance in the themes reminded me of troubleshooting Wordpress builds in the past. I initially used the Bootstrap v4 theme, but when I deployed to Netlify there were additional modifications I needed to create that weren't specified in the theme's config.toml file. As I remember being the non-technical user years ago hoping for a quick way to get content live, I was a bit disappointed to feel like my initial build was 'too simple'  for Netlify-i.e, I didn't initially use any build tools since I was only rendering markdown, no Javascript, no custom CSS outside of the theme. I tried a few permutations for the build command and the publish directory, but when it finished building I had a blank screen with no notable error messages...I'm sure a scenario the existing support engineers have encountered before!

I figured the issue was with the bootstrap theme because it was showing it couldn't pick it up even though it was reading it inside the config.toml file, so I switched it out and rebuild the framework using the sandbox Victor-Hugo repo, and I was able to get everything sucessfully rending on Netlify shortly after.

So ultimately, the only issue was theme configuration with Hugo when I wanted to deploy on Netlify.
