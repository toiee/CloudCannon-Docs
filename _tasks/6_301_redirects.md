---
title: 301 Redirects
---

When you change the structure of your website you might want the old URLs to redirect to new pages for SEO reasons. To set up 301 redirect on CloudCannon, first create a file called 301.txt in the root of your website. In this file you can specify the redirects using this syntax:

{% highlight text %}
old_url new_url
{% endhighlight %}

You can have wildcards by using * and external domains will work too. Here's an example file:

{% highlight text %}
/old_file.html /new_file.html
/category/* /new_category
/page http://google.com
{% endhighlight %}
