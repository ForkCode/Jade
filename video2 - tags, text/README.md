Tags and text
===============

- Karan Goel

### [Watch it on YouTube](https://www.youtube.com/watch?v=VG6LI5D-oUs)

### Tags

- First word is a tag

        p
        div
        h1

- Jade knows self-closing tags

        img
        input

### Text

- Everything after the first word is the text

        p Hello, World

    Try it:

        $ echo "p Hello, World" | jade

- For multiline text, use pipes `|`.

        p
            | Hello, World!
            | This is a block of text.
            | I hope you enjoy using Jade.

- Use normal HTML as well

        p
            | <h1>Hello, World!</h1>
            | This is a block of text.
            | I hope you enjoy using Jade.
