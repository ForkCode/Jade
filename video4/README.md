How to use Jade
===============

### IDs, Classes and Attributes

### Classes and IDs

- Use CSS selectors
- The HTML `class` attribute is `.classname`
- Can have multiple classes
        
        p.lead
        div.row.col-md-6

    For `div`, no need of `div.

        .row.col-md-6

- The HTML `id` attribute is `#idName`

        div#item

- Can combine them

        input#bar.foo1.foo2

### Attributes

- HTML-like in a Javascript syntax

        a(href='google.com') Google
        a(class='button', href='google.com') Google

- Tags can have classes, IDs and attributes

        a.main#header(class='button', href='google.com') Google
