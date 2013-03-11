---
title: HTML & CSS Chapter 1 - 7
date: 2013-03-11 15:19 -06:00
tags:
---

Since the time of xanga, I've always been interested in web design so HTML and
CSS isn't something new to me. However, I was mostly self taught and haven't
kept up with the new HTML5 tags so there were a couple of interesting new
elements in *HTML & CSS*.

###Definition Lists

Definition lists allow you to specify a term and the definition for the term. By
default, it will be displayed so that the definition is indented.

To create a definition list, you start off with the ````<dl>```` tag. For every
term, you sorround it with the ````<dt>```` tag. To give it a definition, you
can use the ````<dd>```` tag.

````
<dl>
  <dt>Sashimi</dt>
  <dd>Sliced raw fish that is served with condiments such as shredded
  radish</dd>
  <dt>Scale</dt>
  <dd>A defice used to accurately measure weight</dd>
</dl>
````

###Abbreviations and Acronyms

The ````<abbr>```` tag indicates that some text is an abbreviation for whatever
you specify in the title attribute. For example ````<abbr title="You only live once">YOLO</abbr>```` would show: <abbr title="You only live once">YOLO</abbr> and if you hover over the text, then you'll what YOLO stands for.

###My Takeaway

None of the chapters were very surprising or had any confusing concepts. For me,
the it was a huge reminder to always thinking of your atypical reader (ie people
who use screenreaders). Without saying it explicitly, the book is adamant about
making sure your webpage is universally accessible by using the appropriate
tags. It also constantly reminds us to keep the look and feel **out** of the
html and in the CSS.

