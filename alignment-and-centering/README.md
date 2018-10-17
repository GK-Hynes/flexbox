# Alignment and Centering

Flexbox is particularly useful for aligning and centering items.

`justify-content` aligns items along the main axis.

The default is `justify-content: flex-start`, which aligns the items to the start of the flex container.

`justify-content: flex-end` will push the items to the end of the flex container.

`justify-content: center` will centre the items along the main axis.

`justify-content: space-between` will start the first item at the flex start, the last item at the flex end, and will divvy up the rest of the space between each item (this has the advantage of requiring less maths than float-based layouts).

`justify-content: space-around` behaves like `justify-content: space-between` but also takes into account the space at the start and end of the flex container.

To take advantage of `justify-content` when the flex direction is set to `column`, you nedd to give the flex container a height.

Setting direction to `column` and `justify-content` to `center` is one effective way of vertically centering content.
