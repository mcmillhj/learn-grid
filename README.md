# Learn CSS Grid

This is a starter repo to learn the basics of CSS Grid.

## Grid Basics

CSS grid is part of CSS3 and allows us to create grid-based layouts that are intuitive and responsive.

_Why grids? You can read up on grid-based design principles [here](https://www.smashingmagazine.com/2017/12/building-better-ui-designs-layout-grids/)._

### Containers and Items

If you're familiar with flexbox, jumping into grid can be pretty smooth.

Like flexbox, grid makes use of containers and items.

You'll notice in our initial setup, there is a div (with a class of `'container'`), that encompasses 26 child div elements (each with a shared class of `'item'` as well as a unique class so we can target individual elements if necessary).

#### ﾟ・:\*☆ TRY IT OUT! ☆\*:・ﾟ

To make a container a grid, we make use of the `display` property, and set its value to `grid`.

```css
.container {
  display: grid;
}
```



### Resources

* [CSS Tricks visual guide to grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
* [Wes Bos's EXCELLENT (and free!) CSS Grid video tutorials](https://cssgrid.io/)
* [Best practices to consider](https://www.smashingmagazine.com/2018/04/best-practices-grid-layout/)
