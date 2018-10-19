# Sizing with the Flex Property

The `flex` property answers the question of what to do with extra space or what to do when there isn't enough space.

By default, the width of the flex items is `auto`, i.e. the width of the content inside them.

Setting them to `flex: 1` will cause all the items to take up the same amount of sace regardless of their content. What happens is that they divvy up any extra available space equally.

If you set one item to `flex: 2` it will get double the amount of the extra space.

Conversely, if there isn't enough room, the item set to `flex: 2` will consume twice as much of whatever space is available.

![Screenshot of flex sizing example](https://res.cloudinary.com/gerhynes/image/upload/q_auto/v1539978376/Screenshot_2018-10-19_Flexbox_Sizing_jiqet0.png)
