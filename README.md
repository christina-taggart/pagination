# Layout Drill Pagination Navigation 
 
##Learning Competencies 

##Summary 

 We're going to learn some fundamentals about styling elements on a web page.  You'll have a set of fixed HTML files to work with and your job is to change the CSS and *only* the CSS to achieve the desired effects.

The [source gist](https://gist.github.com/dbc-challenges/dbfab8097733d67b8e5b) contains a set of files meant to represent a blog article that spans multiple pages.

If you open up any of the `page*.html` pages (the `*` represents any character), you'll find that they follow this format:

1. The name of the blog
2. A title for the article
3. The article body, broken up into sections
4. A very ugly pagination link area

In this challenge you'll use your CSS skills to make that ugly pagination link area look much nicer.  Here are some resources you can use for reference:

- [The &lt;ol&gt; element](https://developer.mozilla.org/en-US/docs/HTML/Element/ol)
- [The *display* declaration](http://www.quirksmode.org/css/display.html)
- [The CSS Box Model](http://css-tricks.com/the-css-box-model/)

## Learning Goals

- More practice with the CSS box model.
- Deepen understanding of the DOM hierarchy.
- CSS styling using colors.

## Objectives

### Style Pagination Links

As closely as you can, edit the `main.css` file so that the navigation bar in all of the blog pages (`page*.html`) looks something like this:

![Pagination Navigation](http://f.cl.ly/items/1k3j430y1U032m0v2I1z/pagination_navigation.png)

Notice that the `<< Previous` and `Next >>` links are not nested within the `<ol>` element.  Why do you think this is the case?

Take note of the use of the `active` and `disabled` classes in the HTML.  You should make sure that your CSS covers these cases and does the following:

- Links with `class="active"` have a dark background and light text color
- Links with `class="disabled"` have a lighter text color against the same background

Make sure to give all of the "buttons" uniform spacing.  Good layout design is all about knowing when and how to enforce visual consistency. 

##Releases
###Release 0 

##Optimize Your Learning 

##Resources