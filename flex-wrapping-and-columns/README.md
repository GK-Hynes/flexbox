# Flex-basis, wrapping and columns

`flex-grow`, `flex-shrink` and `flex-basis` only work on the row they are on, they don't affect the row before or after.

If `flex-wrap` is on and, on account of the items' `flex-basis`, they can't all fit on one row, they will wrap onto another row.

The same thing will happen if `flex-direction` is set to `column` and there is a hard height set. The items will wrap onto another column.

If some items have a specific `flex-grow` or `flex-basis` value, the browser will fit as many into the vertical space as it can before wrapping onto the next column. Any leftover vertical space will be divided according to the items' `flex-grow` value.

If there isn't a hard height set, the items will grow until they reach their `flex-basis` and the browser will scroll vertically.

![Screenshot of wrapping and columns example](https://res.cloudinary.com/gerhynes/image/upload/q_auto/v1540029007/Screenshot_2018-10-20_Flexbox_wrapping_and_columns_pkbzqf.png)
