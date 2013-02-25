---
title: Eloquent Ruby - The Basics
date: 2013-02-17 14:03 -07:00
tags: Eloquent Ruby
---

This week, we began reading Russ Olsen's *Eloquent Ruby*. I read most
of this book a year ago, but that was before I had any experience ruby and was programming in Java. After the first few chapters, all I could think
was "WHAT IS THIS BLACK MAGIC?" I was blown away by the convenient methods of
the enumerable and string classes. The concept of dynamic typing completely
escaped me. It shook my statically typed language foundations, and I couldn't
even begin to understand why someone wouldn't want to know the type of some
object.

After 3 weeks of programming in ruby and rereading Part I of *Eloquent Ruby*,
I have a huge appreciation for the language. It's formed in a way that is really
easy for anyone to read.

###In the beginning...

To understand why I'm loving ruby more and more, you
have to understand a little bit of my background.

Before gSchool I was a Java Software Enginner. I was perfectly happy with the
language until I read Uncle Bob's
*Clean Code*. In his book, Uncle Bob mentions that reading code should be like
reading a book (or something like that..). It should read easily and have
a flow. This message really stuck to me. I've seen and dabbled in a lot of
different languages. I've worked with other programmers and boy is there some
horrendous code out there. You really begin to appreciate well written code that
takes very little to no effort to understand.

So after reading that, I tried my very best to follow Uncle Bob's suggestions.
It was pretty doable for the most part, but at some point, my code would often
breakdown into messy 'for' and 'while' loops, and I just got tired of typing `for (int i ; i < someArray.length ; i ++)` over and over. I had to think carefully about what type of data structures I wanted to use. ArrayList? Set? Vector? Does it even matter? Should I expect any type of Collection? While these types of questions are important to consider, I found that they were distracting me from programming and if I chose the wrong one, there would be a lot of potential refactoring.

###Quick comparisons

Ruby makes it extremely easy to write beautiful, *eloquent*,
readable code. Taking the book's Document example, this is what the code might
look like in Java:

public class Document {
String title;
String author;
String content;

```java
public Document(String title, String author, String content) {
    this.title = title;
    this.author = author;
    this.content = content;

}

public String[] words() {
    return content.split(" ");
}

public int wordCount() {
    words().length;
}

public String getTitle() {
    return title;
}

public String setTitle(String title) {
    this.title = title;
}

public String getAuthor() {
    return author;
}

public String setAuthor(String author) {
    this.author = author;
}

public String getContent() {
    return content;
}

public String setContent(String content) {
    this.content = content;
}
}
```

*Phew* That took a bit of effort. This is a LOT more code than the example in the book. While it's readable, there's a lot of extra stuff in it compared to the ruby version. You must be
explicit about EVERYTHING. Having that much detail can be distracting when
you're looking at the code and simply trying to understand what it does.

Now, going with the book's example again, what if we want Document to use an
Author class? You'd have to change a few things...

```java
public class Document {
String title;
Author author;
String content;

public Document(String title, Author author, String content) {
    this.title = title;
    this.author = author;
    this.content = content;

}

public Author getAuthor() {
    return author;
}

public Author setAuthor(String author) {
    this.author = author;
}

//other methods...

}
```
It's not a lot of work, but wouldn't you rather not have to do anythign at all?
Furthermore, you can instantly see that there's a dependency there. Document
is tied to Author (or interface.. whatever it might be). In Java, it's very easy to create tightly coupled classes. Bad dependencies are everywhere. The code becomes rigid and difficult to handle later on.

###Ruby treats you like an adult

Olsen mentions that Ruby assumes the programmer knows what he or she is doing.
I can access any method I want because I might need it, whether or not it's private, protected, or public. This is power that cold go horribly wrong if used improperly and so I'm curious to know how that flexibility is abused in the real world. So far though, the idea of ruby is perfect to me.
