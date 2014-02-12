Live Coding with the LivingStyleGuide Gem at Up.front.ug
========================================================

This is the result of the live coding session I gave at the [frontend user group of Berlin](http://up.front.ug) on February 11, 2014. It is based on:

* [Middleman](http://middlemanapp.com)—a static website generator
* [Sass](http://sass-lang.com)—a CSS pre processor
* [The LivingStyleGuide gem](http://livingstyleguide.org)—a Sass
  extension to create front-end style guides

**Notice:** The current version of Middleman is not compatible with the
LivingStyleGuide gem due to [this issue](https://github.com/middleman/middleman/pull/1165). It’s already fixed, but not relesed yet. So in the [Gemfile](https://github.com/hagenburger/livingstyleguide-upfrontug/blob/master/Gemfile#L5) you need to use the Github source:

~~~ ruby
gem "middleman", git: 'git@github.com:middleman/middleman.git', branch: 'v3-stable'
~~~


Setup
-----

If [Ruby](http://ruby-lang.org) is installed (by default on Mac OS;
otherwise [read this](https://www.ruby-lang.org/en/downloads/)), do
this:

~~~ bash
git clone git@github.com:hagenburger/livingstyleguide-upfrontug.git
cd livingstyleguide-upfrontug
gem install bundler
bundle
middleman
~~~

Now you can open the style guide in your browser at
<http://localhost:4567/styleguide.html>.


Feedback
--------

Feedback is appricated. Please [open issues](https://github.com/hagenburger/livingstyleguide/issues) if you find bugs, ping me on Twitter @[hagenburger](https://twitter.com/hagenburger) and if you like it, give the [LivingStyleGuide on Github](https://github.com/hagenburger/livingstyleguide) a star and [tweet about it](https://twitter.com/intent/tweet?text=Easily%20create%20front-end%20style%20guides%20with&tw_p=tweetbutton&url=http%3A%2F%2Flivingstyleguide.org&via=Hagenburger
) :)

