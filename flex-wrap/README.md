# Flex-wrap

Flexbox is more forgiving and flexible than float-bsed layouts. It will try to work with the widths that you give it but if it can't it will evenly distribute the flex items.

By default, `flex-wrap` is set to `nowrap` and all items will be on one line.

If you set it to `flex-wrap: wrap;`, the flex items will wrap onto multiple lines, from top to bottom.

Unless you tell them otherwise, flex items will try to take up the full height of their container. If you use `flex-wrap`, they will still try to do this but will also divide the vertical space between themselves.

Setting `flex-wrap` to `wrap-reverse` switches the cross axis to bottom to top. The main axis still stays left to right.

If you set `width` to 33.333% the flex items will fill the horizontal space.

Since `margin` is not part of the box model (unlike padding and border), if you give flex items `margin`, they will have gaps between them.

![Screenshot of flexbox flex-wrap exercises](https://res.cloudinary.com/gerhynes/image/upload/q_auto/v1539893773/Screenshot_2018-10-18_Flex-wrap_gdysnt.png)
