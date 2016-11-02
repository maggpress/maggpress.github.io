---
layout: post
title: New developer attends 90's concert, has blast
---

Web developer [Beth Fitzgerald](http://maggpress.com) attended the I Love The 90's Concert with friends Friday evening. Artist like Rob Base and Salt and Pepa floores. While has beens, Vanila Ice and Color Me Bad flopped. A good time was had by all. 

Tables show the good, bad:

Super Good  | Super Bad
------------- | -------------
Rob Base  | Vanilla Ice
Salt & Pepa  | Color Me Bad

Here's an example of an image, which is included using Markdown:

![Geometric pattern with fading gradient]({{ site.baseurl }}/img/blocflix.png)

Highlighting for code in Jekyll is done using Pygments or Rouge. This theme makes use of Pygments by default.

{% highlight js %}
// count to ten
for (var i = 1; i <= 10; i++) {
    console.log(i);
}
{% endhighlight %}

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

{% highlight js %}
// count to twenty
var j = 0;
while (j < 20) {
    j++;
    console.log(j);
}
{% endhighlight %}

Type Theme uses KaTeX to display maths. Equations such as $$S_n = a \times \frac{1-r^n}{1-r}$$ can be displayed inline.

Alternatively, they can be shown on a new line:

$$ f(x) = \int \frac{2x^2+4x+6}{x-2} $$
