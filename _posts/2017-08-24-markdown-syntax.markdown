---
layout: post
title:  "Markdown Syntax"
date:   2017-08-24 16:53:41 +0200
excerpt: "This is an excerpt for this post"
categories: jekyll theme test
---

This is a test post for the markdown of my own theme.

## Headers

Below are the HTML headings:

#       Heading 1
##      Heading 2
###     Heading 3
####    Heading 4
#####   Heading 5
######  Heading 6

## Body text

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur porta, felis nec imperdiet suscipit, leo mi finibus eros, in tempor elit nunc eget metus. Praesent eu libero porta, consectetur mi non, ullamcorper tortor. Integer sit amet nulla at metus suscipit mollis a eu leo. Praesent lacinia augue non venenatis feugiat. Etiam rutrum augue rhoncus ligula hendrerit pulvinar. Quisque sagittis urna vitae enim posuere hendrerit. Maecenas eleifend sed magna in maximus. Cras porttitor ultrices felis, sed porta metus pharetra eu. Nullam scelerisque, arcu eu pulvinar aliquet, mi metus mattis dui, et lobortis ante ligula ut dui. Sed ac ultrices nibh, vitae porttitor leo. Sed condimentum, urna sit amet mattis vulputate, purus mi interdum purus, ut lobortis velit sapien non velit. Morbi in placerat arcu, ut aliquam elit. Curabitur ac enim nec nisi vehicula volutpat.

Etiam est elit, tempor sed ullamcorper ac, posuere vel risus. Nullam ut aliquet orci. Pellentesque lacinia finibus elit ut varius. Quisque lacus lectus, porttitor sit amet metus sed, rutrum sollicitudin nulla. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Etiam viverra auctor felis, eu porttitor nisl bibendum sit amet. Proin id justo velit. Aliquam sit amet nibh neque. In semper, sapien ut vestibulum dictum, odio nisi porttitor velit, vitae pretium dolor erat at nisi. Sed eu euismod lorem, eget sodales tellus.

## Blockquotes

Styled with **Bootstrap 4** classes. You can provide an author or a source, both or only a quote.

{% include blockquote.html quote="Fusce iaculis ipsum nulla, eu varius orci efficitur quis. Vestibulum pellentesque tortor nunc, nec lobortis risus dapibus vitae." %}

{% include blockquote.html
  quote="Fusce iaculis ipsum nulla, eu varius orci efficitur quis. Vestibulum pellentesque tortor nunc, nec lobortis risus dapibus vitae."
  author="Someone famous"
  %}

{% include blockquote.html  
  quote="Fusce iaculis ipsum nulla, eu varius orci efficitur quis. Vestibulum pellentesque tortor nunc, nec lobortis risus dapibus vitae."
  source="Source Title"
  %}

{% include blockquote.html  
  quote="Fusce iaculis ipsum nulla, eu varius orci efficitur quis. Vestibulum pellentesque tortor nunc, nec lobortis risus dapibus vitae."
  author="Someone famous"
  source="Source Title"
  %}

## Images

If you want to add a centered footer to the image you can use the `image` include.

{% include images.html
  src="https://media.stsci.edu/uploads/image/display_image/3999/low_STSCI-H-p1711c-d-1280x720.png"
  alt="Orion Nebula"
  %}

If you add `#full` to the end of the image url it will display in full bleed. This is implemented with a CSS class, meaning you can use it both with markdown and with the provided include.

![Bubble Nebula](http://imgsrc.hubblesite.org/hvi/uploads/image_file/image_attachment/28735/xlarge_web.jpg#full)

You can combine both for a full bleed image and a footer.
{% include images.html
  src="http://imgsrc.hubblesite.org/hvi/uploads/image_file/image_attachment/27624/xlarge_web.jpg#full"
  alt="Spiral Galaxy NGC 6503"
  %}

## Lists

* This
* is
* an
* unordered
* list

1. But this one
2. is an ordered
3. list

## Emphasis

Sed faucibus orci quam, eu ultrices lectus fringilla sed. Sed vitae consectetur urna, *consectetur* dignissim turpis. Nunc hendrerit, leo non malesuada lobortis, tortor leo feugiat orci, ac molestie urna augue non augue. Vestibulum **condimentum ligula** vitae nibh dignissim, scelerisque tristique enim placerat. Vivamus eleifend felis purus. Nam quis cursus dui. Praesent non iaculis est, aliquet molestie nisi. Quisque eu lorem sed diam interdum ullamcorper. Etiam porttitor efficitur arcu congue **commodo**. Duis ligula nisl, pellentesque in feugiat quis, placerat commodo magna. Donec placerat maximus ligula, eget tempor felis porta eu. Proin ornare purus quis *nibh accumsan*, sed hendrerit purus commodo. *Duis vel scelerisque diam*. Nulla vel ultrices libero.

## Links

All links have the same [look](htps://tosomewhere.net), visited or not. There is an [effect](htps://tosomewhere.net) when you hover them.

## Code

#### Inline

The library you need for basic input and output in c is `stdio.h`. Also, you can compile code by running `gcc mycode.c -o myprogram`

#### Code Blocks

Illustrated with C hello world, using Rouge and github

{% highlight c %}
  #include <stdio.h>

  void main() {
    printf("Hello world!\n");
  }

{% endhighlight %}

{% highlight html %}
<HTML>
  <HEAD>
    <TITLE>Hello, World Page!</TITLE>
  </HEAD>

  <BODY>
    Hello, World!
    </BODY>
</HTML>
{% endhighlight %}

{% highlight python %}
  print "Hello World";
{% endhighlight %}

## Helpers

You can stand out important information of different kinds using an include with some bootstrap classes

{% include alert.html type="notice" text="This is a notice" %}
{% include alert.html type="warning" text="This is a warning" %}
{% include alert.html type="danger" text="This is a danger" %}
{% include alert.html type="tip" text="This is a tip" %}

## KBD

You can also use `<kbd>` tag for keyboard buttons.

{% highlight html %}
<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>
{% endhighlight %}

<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>

Credit to [taylantatli](https://taylantatli.github.io/Moon/markdown-syntax/)
