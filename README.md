# wrong-dependency-version-test

## stack

Running `stack build` works fine

## haskell-language-server

Running `haskell-language-server-wrapper` works fine

## vscode

Opening `src/Foo.hs` produces the following error message

```
<command line>: cannot satisfy -package yesod-job-queue-0.4.0.0
    (use -v for more information) compiler
```
