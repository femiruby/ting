# Ting

Ting is a forked deprecated chinese social networking project written in Ruby on Rails and Semantic-UI.

You can check out the demo at [this link](http://tinger.herokuapp.com).

## Screen Shots

![](http://ww1.sinaimg.cn/large/76dc7f1bgw1ent5zzgeyvj21kw11416d.jpg)

![](http://ww1.sinaimg.cn/large/76dc7f1bgw1ent5xvakuyj21kw114qce.jpg)

![](http://ww4.sinaimg.cn/large/76dc7f1bgw1ent5z2xqrnj21kw114n2c.jpg)

![](http://ww4.sinaimg.cn/large/76dc7f1bgw1ent60hhp39j21kw11443g.jpg)

![](http://ww1.sinaimg.cn/large/76dc7f1bgw1ent60ssvxgj21kw1147aa.jpg)

## Requirements (Windows)

+ Ruby 2.0.0
+ Ruby DevKit 2.0+
+ Bundler

## Easy Install (Windows)
    $ git clone git://github.com/femiruby/ting.git
    $ cd ting
    $ bundler install
    $ rake db:migrate
    $ rails s

## Wicked King Install Guide (Windows)
Download [Chocolatey](https://chocolatey.org/) (Package manager for windows) and open cmd

    cmd> choco install ruby -version 2.0.0.64800
    cmd> choco install ruby2.devkit
    cmd> start cmd
    cmd> gem install bundler
    cmd> cd path/to/ting
    cmd> bundler install
    cmd> rake db:migrate
    cmd> rails s
    
    open localhost:3000 in browser



Copyright (c) 2016 The Blue King

---------------

Released under the MIT license:

* [www.opensource.org/licenses/MIT](http://www.opensource.org/licenses/MIT)
