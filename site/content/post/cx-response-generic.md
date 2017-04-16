+++
date = "2017-04-17T18:32:36-07:00"
draft = false
title = "A Generic Response to A Succinct User Ticket 'site won't build' "

+++

My two main goals are to establish immediate action points for troubleshooting, as well as prompting the user to provide specific information that will help trace to the root of the problem as efficiently as possible.
<hr>
“Hello _______, I’m sorry to hear about the issues with your site. I’ll provide a few steps for troubleshooting, and if you could provide me with the static site generator you’re using, that will aid in making sure your configuration files are set up properly prior to running the build. We want to verify that  also the build is failing through Netlify and that there isn’t an issue with your site generators’ compiling.

-Here are some tips on configuring your site to build depending on the language your site generator is built on (for example, Jekyll is built with Ruby and Hugo is written in Go).

  https://www.netlify.com/docs/#helpful-hints

Are you deploying manually or is your site set for continuous deployment? Take a look at this section under ‘Deploy Context’ https://www.netlify.com/docs/continuous-deployment/

If those tips don’t resolve your issue or you receive a different 'build failed' message, can you please screenshot of your terminal output so I can further diagnose the root of the issue?

Best,

Andrew
<hr>
