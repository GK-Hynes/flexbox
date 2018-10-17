# Flexbox Ordering

Flexbox lets you reorder how your DOM elements appear without actually moving them around in the DOM.

The order property is just `order` and takes a number. By default, everything is set to `order: 0;`.

If you set a flex item's order to anything greater than 0 it will be placed at the end of the main axis.

This is great for responsive design, where you can reorder content for mobile or desktop without changing the HTML.

If you give a flex item an order that is a negative number, it will be moved to the start of the main axis.

Don't reorder areas that people might try to copy text from because the content they select will still be in the order of the HTML. Instead, use it to reorder larger areas, such as "about", "contact", "product info".
