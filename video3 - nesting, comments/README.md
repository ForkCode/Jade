Nesting and Comments
=================

### [Watch it on YouTube](https://www.youtube.com/watch?v=2TMRBSNRQTc)

### Nesting

- Just add a new line and a tab per indent level

        div
            p
                h1 <i>Nesting example</i>
            p
                strong Hello World
            div
                small Say Hi!

### Comments

- Single line comments - just like Javascript

        // just some paragraphs
        p foo
        p bar

- Unbuffered comments

        //- this comment won't show up in HTML
        p this works

- Block comments

        // This is a multi-line comment
            we should add more and more
            to comments
