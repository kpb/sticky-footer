## Sticky-Footer

Your web page has a header, some content, and a footer. If the content isn't vertically long enough to push
the footer down, the footer ends up in the middle of the page - ugly! A lot of solutions use a fixed height
footer, which is great until you load the page in a phone or a tablet.

I found a great solution for making a _responsive_, flexible height, sticky-footer by
[Galen Gidman](http://galengidman.com/author/galen/) - using only CSS -
[here](http://galengidman.com/2014/03/25/responsive-flexible-height-sticky-footers-in-css/)

I love me some [Bootstrap](http://getbootstrap.com), but the
[bootstrap sticky footer](http://getbootstrap.com/examples/sticky-footer/) example is *not* responsive. So, I
created a simple Bootstrap example with a responsive sticky-footer.


### What's Here?

- A simple example, `index.html` and `sticky-footer.css` which only has the bare minimum html/css to create a
  sticky-footer.

- A Bootstrap sticky-footer example, `index-bootstrap.html` and `sticky-footer-bootstrap.css`. The footer is a
  3 column responsive [bootstrap grid](http://getbootstrap.com/css/#grid). Make your browser window narrow -
  like a phone - and you can see how the footer responds to the increased height.


Peace, Kenneth.
