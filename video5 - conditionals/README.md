How to use Jade
===============

### Conditionals

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
