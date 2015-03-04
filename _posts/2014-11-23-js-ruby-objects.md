---
layout: post
title:  "Javascript Objects vs. Ruby Objects"
categories: jekyll update
---

JavaScript and Ruby have some similarities and differences when it comes to creating objects. Both languages require the interaction of other objects in order to create new objects. In Ruby, objects are created from a class. Classes, which work like a blueprint, are responsible for creating objects and for defining the behavior of such objects. But even though classes themselves are objects, they are a special kind of object with different properties than their instances.

JavaScript objects, on the other hand, do not have any explicit classes. Objects can be created using literal notation by setting properties or can also be created from an existing object in which objects inherit from other objects. Using the prototype property provides a way to define the behavior and share it with all objects created by the function. Though Javascript does not contain explicit classes, the prototype property is the closest thing to Ruby classes. So objects in JavaScript are a collection of properties and, like ruby that contains its instance variables, they reference other objects. And JavaScript objects look very similar to Ruby hash objects. However, the method for accessing those variables work differently between JavaScript and Ruby, as Ruby has a higher level of encapsulation than JavaScript does.

For additional info, check out:

[stantona.github.io/blog/2012/12/20/a-tale-of-two-object-models-javascript-and-ruby-part-2/](http://stantona.github.io/blog/2012/12/20/a-tale-of-two-object-models-javascript-and-ruby-part-2/)

[en.wikipedia.org/wiki/Prototype-based_programming](http://en.wikipedia.org/wiki/Prototype-based_programming)