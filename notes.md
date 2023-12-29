# What is flexbox

Flexbox is a way to arrange items into rows and columns. And the items can flex basically grow and shrink. And we are going to be the one who are going to define the rules for em to flex.

## Not just a property but a toolbox

Flexbox isn't just a single CSS property but a whole toolboxx of props that we can use to put things wehre we need em. Some of these props belong on the flex container, while some go on flex items. This is a simple yet imp concept.
A flex container is any element that has `displa: flex;` on it. A flex item is any else that is nested inside the flex container. so in short the child's of the flex container are called flex-item.

Any element can be both a flex container as well as a flex item. We can also put `display: flex;` on a flex item and then use the flexbox to arrange the elemnt's in it / it's children.

## Growing and shrinking

What da heck is `flex:1`?

  The flex shorhand:

The flex declaratoin is a shorthand for 3 props which can be set not on the flex container but on the **flex item**.
These props  affect how flex items size themselves within their container.
Shorthands properties allow us to set value of multiple other css props simultaneously. which saves time and energy and our code becomes more readable.
