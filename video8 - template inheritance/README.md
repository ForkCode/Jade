How to use Jade
===============

## Template Inheritance

### [Watch it on YouTube](https://www.youtube.com/watch?v=pRKxdMjWPHA)

- Define a base that can be used in other places
- A parent defines a `block` that a child must overwrite
- Child can `extends` (inherit) multiple templates
- Can have multiple blocks, inherit multiple levels

#### Difference from `include`

- `include` is used to separate out snippets of code
- inheritance is useful to build a heirarchy of templates
- inheritance build a structure for a file some parts of which can live out of it
- can have different templates based on the same structure
