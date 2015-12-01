# stack-template-demo

[![Build Status](https://travis-ci.org/FranklinChen/stack-template-demo.png)](https://travis-ci.org/FranklinChen/stack-template-demo)

This is a demo of the `franklinchen` Haskell Stack template. It was created with the command

```
$ stack new stack-template-demo franklinchen
```

to pick up my template at https://github.com/commercialhaskell/stack-templates/blob/master/franklinchen.hsfiles

Features of this template:

- A Travis file `.travis.yml` using Stack, and a badge for the README.
- A sample library module `Lib`.
- A sample HSpec/QuickCheck test suite that includes the test module `LibSpec`.
- A sample application in `app`.

Run the tests with

```
$ stack test
```
