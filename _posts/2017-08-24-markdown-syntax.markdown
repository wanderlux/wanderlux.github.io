---
layout: post
title:  "Markdown Syntax"
date:   2017-08-24 16:53:41 +0200
excerpt: "This is a test post for the markdown of my own theme"
categories: jekyll theme test
---

This is a test post for the markdown of my own theme

## Headers

Below are the HTML headings:

#       Heading 1
##      Heading 2
###     Heading 3
####    Heading 4
#####   Heading 5
######  Heading 6

## Body text

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis efficitur vehicula. Sed quis laoreet lacus, ac rutrum est. Cras quam sem, scelerisque a justo at, varius mollis nisi. Nullam pellentesque sapien ut est tincidunt, vel pharetra est iaculis. Nullam vehicula sed tellus scelerisque euismod. Integer vulputate lectus at purus tempus tincidunt. Morbi sapien orci, commodo quis diam at, fermentum lobortis erat. Donec mauris sapien, maximus id ligula non, finibus placerat diam. Vestibulum interdum ut justo eget rhoncus. Vestibulum vitae urna dolor.

## Blockquotes

Fusce iaculis ipsum nulla, eu varius orci efficitur quis. Vestibulum pellentesque tortor nunc, nec lobortis risus dapibus vitae.
{: .blockquote}


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

Sed faucibus orci quam, eu ultrices lectus fringilla sed. Sed vitae consectetur urna, *consectetur* dignissim turpis. Nunc hendrerit, leo non malesuada lobortis, tortor leo feugiat orci, ac molestie urna augue non augue. Vestibulum **condimentum ligula** vitae nibh dignissim, scelerisque tristique enim placerat. Vivamus eleifend felis purus. Nam quis cursus dui. Praesent non iaculis est, aliquet molestie nisi. Quisque eu lorem sed diam interdum ullamcorper. Etiam porttitor *effi*citur arcu congue commodo. Duis ligula nisl, pellentesque in feugiat quis, pla**cerat** commodo magna. Donec placerat maximus ligula, eget tempor felis porta eu. Proin ornare purus quis nibh accumsan, sed hendrerit purus commodo. Duis vel scelerisque diam. Nulla vel ultrices libero.

## Links

[an example link](htps://tosomewhere.net)

## Code

#### Inline

The library you need for basic input and output in c is `stdio.h`. Also, you can compile code by running `gcc mycode.c -o myprogram`

#### Code Blocks

Illustrated with C hello world:

```
    #include <stdio.h>

    void main() {
      printf("Hello world!");
    }
```

## Notices, warnings, dangers and tips

You can stand out important information of different kinds using an include with some bootstrap classes

{% include alert.html type="notice" text="This is a notice" %}
{% include alert.html type="warning" text="This is a warning" %}
{% include alert.html type="danger" text="This is a danger" %}
{% include alert.html type="tip" text="This is a tip" %}

## KBD

You can also use `<kbd>` tag for keyboard buttons.
```
<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>
```
<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>

Credit to https://taylantatli.github.io/Moon/markdown-syntax/
