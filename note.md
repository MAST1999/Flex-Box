# Flex Box

## What is flex box

Flex box is a way of targeting multiple elements and wrapping them up in a single box. In this box you can set different options for order and how the box reacts to browser resizing.

## Flex Direction

This property indicates the order in which the items are placed and possible values include:

- row
- row-reverse
- column
- column-reverse
- and a few more

## Flex Wrap

As the name suggests it wraps the box if the size of elements exceed the browser size it indents them so that they stay visible. Possible values include:

- wrap
- nowrap
- wrap-reverse
- and a few more

## Justify Content

The `justify-content` property aligns the flexible container's items when the items do not use all available space on the main-axis (horizontally).

Use the align-items property to align the items vertically.

## Align Items / Align Content

The `align-items` property specifies the default alignment fot items inside the flexible container.

Use the align-self property od each item to override the `align-items` property.

The `align-content` property modifies the behavior of the `flex-wrap` property. Ut us similar to `align-items`, but instead of aligning flex items, it aligns flex lines.

There must be multiple lines of items for this property to have any effect.

Use the `justify-content` property to align the items on the main-axis(horizontally).
