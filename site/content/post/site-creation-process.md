+++
date = "2017-04-15T18:32:36-07:00"
draft = false
title = "How Did I Make This Site, What Tools Were Used, and Were There Challenges?"

+++

To be completely forthcoming, I started off exploring Jekyll for a bit but changed to Hugo. Ruby is my strongest language which would result in the least amount of time getting up to speed with the configurations in Jekyll, but I had heard a lot about Hugo and also had only glanced at Go before. I also disliked how Jekyll comes configured specifically for a ‘Post’ style of blog right out of the box.

With Hugo, the scaffolding creates a more bare-bones style setup and only through installing and configuring a theme does it end up with the structure of a blog. Because of this, I felt more flexibility in exploring Hugo, and I've never seen anything build as quickly as it does on top of Go.

 My main challenge with Jekyll was figuring out why newly created HTML would be reverted to the boilerplate whenever I added a custom partial (i.e., a nav bar) into the _ _includes_ directory. It was because of the `bundle exec jekyll serve —watch` command I ran after initialization.

I had zero issues with Hugo, and I found their documentation + examples to be more coherent.
