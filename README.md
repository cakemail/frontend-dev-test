# editor-test

Hi !

Let me propose a little challenge.

You must create an object oriented system that allows a user to insert an emoji icon into a content-editable _div_, with the help of a tooltip, at the caret position.

Here's what it could look like:

1. On click, inside the content editable _div_, a tooltip should appear, presenting the list of available emojis ![Step 2](http://i.imgur.com/FYGqlD9.png)
2. Clicking on an emoji should insert it at the caret. ![Step 3](http://i.imgur.com/0y5X6gp.png)

First, here's what you are given:
  - A _div_ with editable content
  - jQuery

Here's what you can't use:
  - You cannot use jQuery plugins. We let you use jQuery itself, and that should be enough.

And here's what we want:
  - A tooltip object
    - The tooltip must accept a X number of components (think of components as tools that can can be listed in the tooltip)
  - An object for each emoji (think of them as components)
  - All object oriented
  
Remember, we want to see what you are capable of. The use of other resources should be used only to help your code, not do it for you !
