# Parsing Expression Grammar Notation

We use (Pest-Rust) to write our grammar based on official
[PEGN](https://pegn.dev/).

Comparison with peg and regex.
[read](https://guitarvydas.github.io/2021/03/19/Racket-PEG.html) more about
that.

## Symbols and Rules

- Curly Braces `{}`: As start to define new line of grammar for a variable you
  must define grammar between a Curly Braces
- ASCII_DIGIT: Contains all ASCII digital numbers
- Plus `+`: is just like Regex, continue expression
- Asterisk `*`: Is just like +, repeat pattern zero or more time
- Tilde `~`: Is just like And to concatenate two things, "abc" ~ "def" ->
  "abcdef"
- SOI: Start of Input
- EOI: End of Input
- [see more](http://stackoverflow.com/questions/15433188/ddg#15433225)