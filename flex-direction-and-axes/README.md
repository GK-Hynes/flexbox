# Flex-direction and Axes

`flex-direction: row;`

The default flex-direction is row. The flex items will stack horizontally beside each other and span vertically to the height of the container.

`flex-direction: column;`

Setting the flex-direction to column will stack the flex items vertically.

Whether you set the container to `flex-direction: row;` or `flex-direction: column;` you will have two axes: the main axis and the cross axis.

When set to `row`, the main axis is from left to right. The cross axis is from top to bottom.

When set to `column`, the main axis is from top to bottom (which is why the content stacks vertically) and the cross axis is from left to right.

`flex-direction:row-reverse;` sets the main axis from right to left.

`flex-direction:column-reverse;` sets the main axis from bottom to top.

![Screenshot of flex-direction exercises](https://res.cloudinary.com/gerhynes/image/upload/v1539893711/Screenshot_2018-10-18_Flex_Direction_and_Axes_akjfxt.png)
