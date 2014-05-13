How to use Jade
===============

### Loops

### [Watch it on YouTube](https://www.youtube.com/watch?v=GP_yMnBKBjw)

- Iteration over arrays or objects

        ul
            each val in [1, 2, 3, 4, 5]
                li= val

- Can also use `for` keyword

        ul
            for val in [1, 2, 3, 4, 5]
                li= val

- Can get index while iteration

        ul
            each val, index in ['zero', 'one', 'two']
                li= index + ': ' + val

- And iterating over keys in objects

        ul
            each val, index in {1:'one',2:'two',3:'three'}
                li= index + ': ' + val
