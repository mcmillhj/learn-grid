# Learn CSS Grid

This is a starter repo to learn the basics of CSS Grid.

## SETUP

_Note: you'll need node.js on your computer_

1. [Download Firefox](https://www.mozilla.org/en-US/firefox/new/) (we'll be using Firefox's CSS grid dev tools)
2. Clone down the repo: `git clone https://github.com/letakeane/learn-grid.git`
3. Install the dependencies: `npm install`
4. To fire up the server, run `npm start`

## Grid Basics

CSS grid is part of CSS3 and allows us to create grid-based layouts that are intuitive and responsive.

_Why grids? You can read up on grid-based design principles [here](https://www.smashingmagazine.com/2017/12/building-better-ui-designs-layout-grids/)._

### Containers and Items

If you're familiar with flexbox, jumping into grid can be pretty smooth.

Like flexbox, grid makes use of containers and items.

You'll notice in our initial setup, there is a div (with a class of `'container'`), that encompasses 26 child div elements (each with a shared class of `'item'` as well as a unique class so we can target individual elements if necessary).

Like flexbox, we'll turn the container into a grid, and the items inside it will be the elements of the grid.

We can specify the size and location of our elements, or allow them to flow naturally into the available space of the grid.

#### ﾟ・:\*☆ TRY IT OUT! ☆\*:・ﾟ

Right now, this is what we see when we start up our server and navigate to our html file:

![page-width div elements stacked in a single column containing various emojis](https://media.giphy.com/media/9oIrQRccl2OA9DKuos/giphy.gif)

To make a container into a grid, we make use of the `display` property, and set its value to `grid`.

```css
.container {
  display: grid;
}
```

Now, nothing appears different, but if we open up our dev tools, click the `Layout` tab, and check the box next to `div.container`, we can see that our container is now a grid.

![container and items with firefox grid inspector tools](https://i.imgur.com/RxlAD2X.png)

If we zoom in, we can see that there are a couple different types of lines here:

![zoomed in on grid inspector lines](https://i.imgur.com/dyVPK9n.png)

We'll get into what these indicate later - for now, note that the solid line is the edge of the grid in its entirety.

We also have these numbers, as well, which describe the lines surrounding our grid items.

## Templating



### Resources

* [CSS Tricks visual guide to grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
* [Wes Bos's EXCELLENT (and free!) CSS Grid video tutorials](https://cssgrid.io/)
* [Best practices to consider](https://www.smashingmagazine.com/2018/04/best-practices-grid-layout/)
