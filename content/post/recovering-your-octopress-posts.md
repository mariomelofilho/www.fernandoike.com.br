+++
title = "Recovering your octopress posts"
date = "2014-06-03"
draft = true
Categories = []
+++
Sometimes I make stupidy things. I delete my blog directory in my computer and
I give thinking what I could do to recovery my posts.

I didn't want rewrite post manually, so I wrote a little ruby script to do
this for me. 

The idea is get the posts and convert to markdown. The cool thing that is easy to convert again to markdown beacause my blog was generated by Octopress.

In begin, I thougth in read and parse the sitemap.xml file and
get posts by year.
