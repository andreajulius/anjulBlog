---
layout: post
title:  "Jekyll Lingo & Command Lines!"
categories: jekyll update
---

Lingo:

- <b>Front matter</b>: Can be written in JSON or YAML. Both are written in "Key: value" pairs, like this:

{% highlight ruby %}
---
layout: post
title:  "Jekyll lingo & Command lines!"
categories: jekyll update
---
#=> the attribute 'layout' is equal to the value 'post'
{% endhighlight %}



- <b>Liquid tags</b>: are the programming logic that tells templates what to do.

{% highlight ruby %}
{ % for product in collection.products % }
  {.{product.title}.} #=> The full stops between the braces were included so they show up on the example
{ % endfor % }
#=> example courtesy of Shopify.
{% endhighlight %}

Jekyll also has some very useful Filters, which are too many to list on this site: <a href="https://jekyllrb.com/docs/liquid/filters/">Liquid Filters</a>

For ALL command lines click here: <a href="https://jekyllrb.com/docs/usage/">Commands</a>
