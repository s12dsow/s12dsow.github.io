---
layout: post
title:  "What are Classes?"
categories: jekyll update
---


I like to think of classes as the blueprints which allow you to create as many objects as you want. It sets the guidelines, or provides the state and behavior for the objects. Once the objects are created from this blueprint, they can be modified to do and hold different things. A great example I learned is with cars. For example, there is a specific blueprint that is used to create a car. But from that blueprint, lots of different cars can be created, with different colors, sizes, engines, number of doors, etc. We already have some built-in classes that we use in our code already, such as String, Fixnum, Float, Array, Hash, etc.

And now to go along with classes, we use instance variables that are scoped to class and can be accessed from any method within the class. To create an instance variable, you would preface the variable with an @ sign, such as @variable. So, the state of an object is the instance variable, or also what an object knows about itself, and methods are the things that an object can do.

Let us say that we want to create a class that does basic calculator functions such as adding, subtracting, multiplying and dividing of two variables x and y that were created as instance variables:

We could do:

{% highlight ruby linenos %}
	class Calculator
  def initialize
    @x = 10
    @y = 5
  end

  def add
    @x + @y
  end

  def subtract
    @x - @y
  end

  def divide
    @x / @y
  end

  def multiply
    @x * @y
  end
end

calculator = Calculator.new
puts calculator.add
puts calculator.subtract
puts calculator.divide
puts calculator.multiply
{% endhighlight %}