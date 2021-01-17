# Javascript
description

## CSS -> flexbox

There are several options for how to space the flex items along the line that is the main axis. One of the most commonly used is __justify-content: center;__, which aligns all the flex items to the center inside the flex container. Others options include:

* __flex-start__: aligns items to the start of the flex container. For a row, this pushes the items to the left of the container. For a column, this pushes the items to the top of the container. This is the default alignment if no justify-content is specified.
* __flex-end__: aligns items to the end of the flex container. For a row, this pushes the items to the right of the container. For a column, this pushes the items to the bottom of the container.
* __space-between__: aligns items to the center of the main axis, with extra space placed between the items. The first and last items are pushed to the very edge of the flex container. For example, in a row the first item is against the left side of the container, the last item is against the right side of the container, then the remaining space is distributed evenly among the other items.
* __space-around__: similar to space-between but the first and last items are not locked to the edges of the container, the space is distributed around all the items with a half space on either end of the flex container.
* __space-evenly__: Distributes space evenly between the flex items with a full space at either end of the flex container
