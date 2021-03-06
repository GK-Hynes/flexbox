# Alignment and Centering

Flexbox is particularly useful for aligning and centering items.

## Justify-content

`justify-content` aligns items along the main axis.

The default is `justify-content: flex-start`, which aligns the items to the start of the flex container.

`justify-content: flex-end` will push the items to the end of the flex container.

`justify-content: center` will centre the items along the main axis.

`justify-content: space-between` will start the first item at the flex start, the last item at the flex end, and will divvy up the rest of the space between each item (this has the advantage of requiring less maths than float-based layouts).

`justify-content: space-around` behaves like `justify-content: space-between` but also takes into account the space at the start and end of the flex container.

To take advantage of `justify-content` when the flex direction is set to `column`, you nedd to give the flex container a height.

Setting direction to `column` and `justify-content` to `center` is one effective way of vertically centering content.

![Screenshot of justify-content example](https://res.cloudinary.com/gerhynes/image/upload/q_auto/v1539894957/Screenshot_2018-10-18_Flexbox_Alignment_and_Centering_2_qbbt1q.png)

## Align-items

`align-items` aligns items along the cross axis. By default, it is set to `align-items: stretch`, where items will stretch to fill the container.

`align-items: flex-start` aligns items at the start of the cross axis.

`align-items: flex-end` aligns items at the end of the cross axis.

`align-items: center` will centre them on the cross axis.

`align-items: baseline` will align items along the baseline of their content.

![Screenshot of align-items example](https://res.cloudinary.com/gerhynes/image/upload/q_auto/v1539894946/Screenshot_2018-10-18_Flexbox_Alignment_and_Centering_1_q1mshd.png)

## Align-content

While `justify-content` works on the main axis, `align-content` works on the cross axis. It only works when you have multiple lines of content.

The default is `align-content: stretch`, where lines stretch to take up the remaining space.

`align-content: flex-start` packs the lines at the start of the cross axis.

`align-content: flex-end` packs the lines at the end of the cross axis.

`align-content: center` centres the lines on the cross axis.

`align-content: space-between` puts the first line at the start of the axis, the last at the end, and evenly distributes the space between.

`align-content: space-around` evenly distributes the space around each line.

You can use `align-content` and `justify-content` together to centre straggling items.

![Screenshot of align-content example](https://res.cloudinary.com/gerhynes/image/upload/q_auto/v1539893730/Screenshot_2018-10-18_Flexbox_Alignment_and_Centering_kc85pb.png)

# Align-self

`align-self` works exactly like `align-items` but you can apply it on a case by case basis to individual items. So, for example, you could have all items aligned to `flex-start` but one item aligned to `flex-end`.

![Screenshot of align-self example](https://res.cloudinary.com/gerhynes/image/upload/q_auto/v1539977402/Screenshot_2018-10-19_Flexbox_Alignment_and_Centering_shk1jz.png)
