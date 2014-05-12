Curtis LESS Typeface
====================

**Curtis** is the name given by *Dave DeSandro* to a family of geometric sans-serif fonts. Other incarnations exist as Fontstructions: [Curtis Heavy](http://fontstruct.fontshop.com/fontstructions/show/180805) and [Curtis Pixel 14](http://fontstruct.fontshop.com/fontstructions/show/curtis_pixel_14).

The **Curtis LESS version**, which is based on the [Curtis CSS font](http://desandro.github.io/curtis-css-typeface), takes form in CSS compiled from LESS for added parametric options. All shapes are rendered in the browser, using a combination of background color, border width, border radius, and a heavily reliance on absolute/relative positioning.

Each character is wrapped in a `<span>` and then depending on the complexity of that character, more empty `<span>` elements are added to the markup to render each shape. Here's the markup for R:

``` html
<span class="css_char r">
  R
  <span class="inside split_vert"></span>
  <span class="outside split_vert"></span>
  <span class="stroke"></span>
  <span class="fill"></span>
</span>
```

The [Curtis CSS typeface](http://desandro.github.io/curtis-css-typeface) is an original project by [Dave DeSandro](http://desandro.com).
The [Curtis LESS typeface](http://xuv.github.io/curtis-less-typeface) is an adaptation of Dave's work by [Julien Deswaef](http://xuv.be) using LESS with the intention of having more flexible font sizes and colors while keeping all the original ideas from the Dave's design.

This design pattern is released under a [Creative Commons Attribution License](http://creativecommons.org/licenses/by/3.0/us/). You are free to share and remix this work.
