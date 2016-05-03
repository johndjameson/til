Layout
======

Wrapping layouts
----------------

You can wrap a Middleman layout with another Middleman layout. For example, to wrap the article layout with `layouts/layout.haml`, you can do the following in `layouts/article.haml`:

```haml
= wrap_layout :layout do

  %article
    - # ...
```
