---
layout: post
title:  "Rise of Ethereum"
date:   2016-09-05
excerpt: ""
tag:
- ethereum
- rise
- video
comments: true
---
<iframe width="560" height="315" src="//www.youtube.com/embed/psg5PUVemdE" frameborder="0" allowfullscreen> </iframe>
{::comment}
Video embeds are responsive and scale with the width of the main content block with the help of [FitVids](http://fitvidsjs.com/).

Not sure if this only effects Kramdown or if it's an issue with Markdown in general. But adding YouTube video embeds causes errors when building your Jekyll site. To fix add a space between the `<iframe>` tags and remove `allowfullscreen`. Example below:

{% highlight html %}
<iframe width="560" height="315" src="//www.youtube.com/embed/SU3kYxJmWuQ" frameborder="0"> </iframe>
{% endhighlight %}
{:/comment}