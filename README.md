# Assignment 1: Haskell Basics

In this assignment you learn the basics of the Haskell programming language.
It is very important to work carefully through the assignment, since the next five weeks build
up on this fundament!

The different topics of this assignment are all covered by the first part of the excellent and strongly recommended book ["Programming in Haskell"](https://www.cs.nott.ac.uk/~pszgmh/pih.html) by Graham Hutton.

## Instructions
1. Install [ghcup](https://www.haskell.org/ghcup/).
2. Use ghcup to install the recommended versions of ghc and cabal: 
   - ghc version 9.4.8 \
   `> ghcup install ghc 9.4.8`
   - cabal version 3.10.3.0 \
   `> ghcup install cabal 3.10.3.0`
3. Install [VS Code](https://code.visualstudio.com/).
4. Install the [Haskell Extension](https://marketplace.visualstudio.com/items?itemName=haskell.haskell)
5. Open VS Code directly on the folder `AS1_HaskellBasics`.
6. Open the file [Main.hs](./Main.hs) and start working through it top to bottom.

## Commands
- Run all tests: `cabal test --test-show-details=direct`
- Only run tests for a particular section:\
   `cabal test --test-show-details=direct --test-option=--match --test-option="8."`
- Start a REPL: `cabal repl test:tests` \
This starts ghci (a read eval print loop) to experiment with your code.
Save your file after making changes and reload it into the repl using `:reload` or `:r`.
`:q` terminates the session.
`:t e` prints the type of expression e.
