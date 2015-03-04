---
layout: post
title:  "Arrays vs. Hashes"
categories: jekyll update
---

Arrays and hashes are similar, and yet different. Both are used to contain and retrieve data and are extremely useful when you have to store variables and keep them in some kind of order. Arrays are more orderly and use integers with its indexing starting from [0]s. For example, if you wanted to store an array of potential girl names, you would define an array, which can be done in a multitude of ways. One of the ways is simply to have an array holding the string of names using the literal constructor:

{% highlight ruby%}
girl_names = ["Layla", "Mina", "Amira", "Maira"] 
{% endhighlight %}


The indexes would then be assigned as follows:

{% highlight ruby %} 
girl_names[0] = "Layla" 
girl_names[1] = "Mina"
girl_names[2] = "Amira"
girl_names[3] = "Maira"
{% endhighlight %}

Now if you wanted to add names to the array later, you could just create an empty array: 

{% highlight ruby %}
girl_names = Array.new 
{% endhighlight %}

or 

{% highlight ruby %}
girl_names = []
{% endhighlight %}

In comparison, hashes are based on collection of key-value pairs and order is not as important as it is with arrays. Like arrays, hashes are indexed, but can be indexed from anything and its key must be unique, with only one key-value pair, unlike an array that can have several copies of the same thing. Now, say you had 4 girls and wanted to list out their ages. You could do it like this:

{% highlight ruby %}
girl_ages = { "Layla" => 10,
"Mina" => 15,
"Amira" => 20,
"Maira" => 20
}
{% endhighlight %}

And to access those values, you would use the same structure as with arrays, except use the special key within the bracket. And if you also wanted just to create an empty hash, you could simply do: 

{% highlight ruby %}
girl_ages = Hash.new
{% endhighlight %}

or 

{% highlight ruby %}
girl_ages = {}
{% endhighlight %}

Another difference has to do with iteration. When you iterate over hashes, two values are passed to the blocks, instead of just one for arrays. Though Arrays and Hashes may be similar, they are unique in their construction and should be used accordingly.