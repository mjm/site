---
layout: post
title: "RubyMotion: Ruby for iOS"
date: 2012-05-03 15:22
comments: true
categories: Software iOS Development
---

[RubyMotion][] is a new software development package for making iOS apps with Ruby. Just looking over their site, there's a lot to like, especially if you're the type who's not so fond of [Xcode][], although I would personally disagree.

<!--more-->

[RubyMotion][] uses a command-line workflow for developing your applications that looks a lot like developing a Rails application. A simple `motion create MyApp` creates a skeleton application, and you use a Rakefile to test and run your app.

There is one place where I think the RubyMotion developers are going in the wrong direction. By sidestepping Xcode, developers are missing out on one of the best parts of iOS application development: Interface Builder. While it's certainly possible to create Cocoa Touch UIs programmatically, it's not nearly as intuitive and pleasant as creating them in Interface Builder.

I think the [RubyMotion][] developers should have embraced the best-in-class GUI designer tools that are already available for iOS development. Otherwise, I like the efforts they are making here.

[RubyMotion][] does come at a price: $199, though currently it's on sale for $149. I'm not sure I'm sold on spending so much on an unproven development environment, especially when I'm not so convinced that it's significantly better than the free tools from Apple. That said, I'm interested to see where this goes.

[rubymotion]: http://rubymotion.com
[xcode]: https://developer.apple.com/xcode/
