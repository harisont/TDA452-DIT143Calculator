If you had trouble with the libraries required for lab 4, this hopefully solves the problem:

1. if you haven't already, [install stack](https://www.haskell.org/downloads/#stack)
2. clone/download this repository
3. move the repository folder
4. run `stack build`.

Unless this fails, you should be good to go: stack installed everything you need _locally to your project folder_ for you, based on the config files (`stack.yaml` and `calculator.cabal`. Take a look if you want). 

Now you can, for instance, run:

- `stack build` to rebuild after you make changes
- `stack exec Calculator` to execute the program
- `stack ghci` to evaluate expressions in the interpreter.

If you are, unlike me, very curious about stack [here is the user guide](https://docs.haskellstack.org/en/stable/GUIDE/).
