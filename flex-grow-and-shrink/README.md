# Flex Grow, Shrink, and Basis

The `flex` property really contains three properties.

`flex-grow` decides how much items will grow if there is extra space. The default is 0, i.e. don't take up any extra room.

If you have two items and set one to `flex-grow: 1` and the other to `flex-grow: 2`, the second will get twice as much of the extra available room.

`flex-shrink` decides how much items will shrink if there isn't enough room. The default is 1, i.e. shrink equally.

`flex-basis` describes how wide the flex items should be by default before the extra space is divided. If `flex-basis` is set to `auto`, the extra space is divided according to `flex-grow`.

The `flex` shorthand describes `flex-grow`, `flex-shrink`, and `flex-basis` in that order.

```css
.box1 {
  flex: 10 5 400px;
}
```

![Screenshot of flex grow and shrink examples](https://res.cloudinary.com/gerhynes/image/upload/q_auto/v1539979816/Screenshot_2018-10-19_Flex_Grow_and_Shrink_fhzdy6.png)
