Haml Tags
=========

You can argue an object into a tag.

```haml
:ruby
  options = {
    alt: 'An example image'
    src: 'https://example.com/image.jpg',
  }

%img{ options }
````

You can’t define `class` inside the object, so you’ll need to define it inside the tag’s object.

```haml
:ruby
  options = {
    alt: 'An example image'
    src: 'https://example.com/image.jpg',
  }

%img{ options, class: 'db mbl mhc' }
````
