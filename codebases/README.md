# Codebases

This is a list of suggested codebases to explore, grouped by programming
language.

Keep in mind that codebases evolve, so the comments here may get out of
date.

## Javascript

- [express](https://github.com/expressjs/express): widely used and written in
  plain javascript. This is a great example of how learning the internals of
  something will improve how you use it (or at least you'll understand
  better what you are doing).
- [sinon](https://github.com/sinonjs/sinon): has to deal with a lot of language
  edge cases, which may or may not be something you consider fun. Also, you have
  to wonder how something like this is tested.

## Scala

- [scalachess](https://github.com/ornicar/scalachess): written in functional
  style, so it may not be representative of most "real world" scala. Still,
  useful to familiarize yourself with how the language works.

## VimL

- [vim-commentary](https://github.com/tpope/vim-commentary): single file plugin,
  but if you are just starting with VimL you will learn a lot.
- [linediff](https://github.com/AndrewRadev/linediff.vim): a more advanced
  plugin (but not too much). And it has tests, which is a plus.

## Haskell

- [network-simple](https://hackage.haskell.org/package/network-simple) 
  is a _low-level-but-not-so-low-level_ library for dealing 
  with TCP network connections in Haskell, both from the server side and client
  side. The library code is rather clean, and it showcases exception handling, 
  resource management, documentation and ergonomic API design.

- [safe-money](https://hackage.haskell.org/package/safe-money) 
  is a library for precisely representing and manipulating 
  monetary amounts (fiat currencies, cryptocurrencies, precious metals). This 
  library showcases type-level programming and API design, as well as
  documentation, testing, higher rank types and serialization. There is a long 
  article explaining this library at https://ren.zone/articles/safe-money
  
- [di-core](https://hackage.haskell.org/package/di)
  is a logging library that relies heavily in _contravariance_ to separating 
  the logging intention from the final rendering format, time, and place. As 
  such, it is an intresting codebase to learn about _contravariance_. Moreover,
  its a very small and ergonomic library with vastly more documentation than 
  code, so it is useful for learning about API design and documentation 
  practices. 
  
