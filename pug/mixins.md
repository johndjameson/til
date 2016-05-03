Mixins
======

Here’s how to declare a mixin:

```jade
mixin placeholdit(width, height)
  img(src='https://placehold.it/#{width}x#{height}' width=width height=height)
```

And then use it like this:

```jade
+placeholdit(480, 360)
```
