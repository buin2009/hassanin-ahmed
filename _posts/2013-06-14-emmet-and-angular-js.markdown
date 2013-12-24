---
layout: post
title:  "Emmet and Angular JS"
date:   2013-06-14 21:26:52
categories: Web Development
author: Hassanin Ahmed 
---

They say a good developer is a lazy developer. I’ve got lazy down to an art, not sure about the rest of it.

One of my favorite plugins to “increase productivity” is Emmet, formerly known as Zen Coding. It is a very popular plugin that is available on multiple platforms that improves your CSS/HTML workflow.

I will not go into the basics as it is available on the documentation but I will show you how to use it with Angular JS directives using square brackets.
{% highlight ruby %}
[ng-click="getName()"]
<!-- This will generate the following -->
<div ng-click="getName()"></div>
{% endhighlight %}

Simple directive

{% highlight ruby %}
ul>li[ng-repeat="todo in todos"]
<!-- This will generate the following -->
<ul><li ng-repeat="todo in todos"></li></ul>
{% endhighlight %}
Nested statement

There is so much more that Emmet can help you produce. Here is the cheatsheet. Go crazy with it.