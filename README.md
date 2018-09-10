# Awesome

This is a toy language called _Awesome_ I'm building based on the instructions
in [How To Create Your Own Freaking Awesome Programming Language][1] by
Marc-André Cournoyer.

[1]: https://www.goodreads.com/book/show/9640000-how-to-create-your-own-freaking-awesome-programming-language

Here are the language guidelines, taken directly from the book.

- As in Python, blocks of code are delimited by their indentation.
- Classes are declared with the class keyword.
- Methods can be defined anywhere using the def keyword.
- Identifiers starting with a capital letter are constants which are globally
  accessible.
- Lower-case identifiers are local variables or method names.
- If a method has a receiver and no argument, parenthesis can be skipped, much
  like in Ruby. Eg.: self.print is the same as self.print().
- The last value evaluated in a method is its return value.
- Everything is an object.

### Setup

```
$ git clone http://github.com:jwworth/awesome.git
$ cd awesome
$ rvm install ruby-2.5.1
```

### Testing

Run a test with:

```
$ ruby -Itest test/lexer_test.rb
```
