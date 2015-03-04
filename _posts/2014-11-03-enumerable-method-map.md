---
layout: post
title:  "Map: An Enumerable Method"
categories: jekyll update
---

The map method is very useful and is considered an enumerable method. The great thing about enumerable methods is that these methods have already been created, and you just have to call on them, instead of having the write the code out over and over again. The map method can take an object and a block and runs the block for each element, creating a new array with the values returned. It is also known as the collect method, as they both do the same thing. In comparison, the destructive version is called map! and instead of returning a new array, it modifies the existing array. There are many reasons you can use map. For example, let us say you have an array of integers and you want to multiply each element by two. Using the map method, you can easily do so: 

{% highlight ruby%}
[1, 2, 3, 4].map {|i| i * 2} 
{% endhighlight %}

You would then return: 

{% highlight ruby%}
[2, 4, 6, 8] 
{% endhighlight %}

And if you used map!, it would look like this: 

{% highlight ruby%}
[1, 2, 3, 4].map! {|i| i * 2}
{% endhighlight %}

It would then modify the existing array, instead of returning a new one. There are many other uses for this method. For more resources, check out the ruby docs: 

[www.ruby-doc.org/core-2.1.4/Array.html#method-i-map](http://www.ruby-doc.org/core-2.1.4/Array.html#method-i-map)