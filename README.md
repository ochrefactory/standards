# Standards

Coding and development standards adopted by our team.
To start off, follow these guidelines:

* Write readable code.
* Simplify code wherever possible.
  Max Kanat-Alexander said it well:
  “How Simple Do You Have to Be?
  […] *Stupid, dumb simple*.”
  (From [Code Simplicity](http://www.codesimplicity.com/book/))
* Be consistent.
* Don’t rewrite existing code to follow these standards,
  except as part of a small refactoring.
  Please don’t change the whitespace of an entire project
  when actively developing it with a team.
* If you need to violate a rule,
  make sure you are doing it to uphold readability and simplicity,
  or at least make sure you can convince a teammate.

## General Rules

### Spacing

Here are some global rules for whitespace
which may be overridden,
depending on the language:

* Use spaces, not tabs. (notable exception: Makefiles)
* Use 2 spaces for indentation
* Keep line-lengths below 80 characters when possible.
* In documentation, prose and comments,
  use [semantic linefeeds](http://rhodesmill.org/brandon/2012/one-sentence-per-line/)

### Documentation

Wherever possible, write top-level documentation for projects.

* Take the opportunity to concisely explain your purpose.
* Write basic usage documentation when appropriate.
* *Never* let documentation get out of sync with existing code.

### Comments

* Use comments in your code to explain the “why,”
  and the “how” should be clear from your code.
  Short use-case examples are also appropriate as comments.

* *Always* keep your comments up-to-date:
  comments and code should never be in conflict.
* Never comment out code: that’s what git is for.

## Language-specific standards

* [Ruby](/ruby.md)
* [CSS](/css.md)

## Interesting reading, works cited:

* Max Kanat-Alexander’s [Code Simplicity](http://www.codesimplicity.com/book/)
* thoughtbot, inc’s [guides](https://github.com/thoughtbot/guides)
