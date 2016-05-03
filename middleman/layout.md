Layout
======

Wrapping layouts
----------------

You can wrap a Middleman layout with another Middleman layout. For example, to wrap `layouts/article.haml` with `layouts/layout.haml`, you can do the following:

```haml
= wrap_layout :layout do

  %article
    - # ...
```
