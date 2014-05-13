How to use Jade
===============

### Conditionals

### [Watch it on YouTube](https://www.youtube.com/watch?v=AhUyWZfAVoA)

- Simple `if/else` statements just like Javascript
- No braces (yay)

        - var channel = "ForkCode"
        if channel == "ForkCode"
            p Awesome
        else
            p Not awesome

- `unless` is negative evaluation

        - var channel = "CrappyChannel"
        unless channel == "ForkCode"
            p Awesome

- `unless channel == "ForkCode"` is equivalent to `if channel != "ForkCode"`
