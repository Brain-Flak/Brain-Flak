# Rand-Flak

Brain-Flak is an "Turing-tarpit", e.g. a language which can, *in theory* compute anything, but in reality is very inconvenient and painful to use. It was heavily inspired by [Brainf**k](https://esolangs.org/wiki/Brainfuck), the original turing-tarpit.

If you are not familiar with Brain-Flak, you should check that out [here](https://github.com/DJMcMayhem/Brain-Flak).

Rand-flak is a variation of Brain-Flak that adds one new nilad and one new monad so that it can compete in challenges requiring non-deterministic output. The two new atoms are:

 - `/\` Evaluates to 0 or 1 randomly, and
 - `/...\` Evaluates to a random number in the range `[0, abs(n)]`, where *n* is the value of the snippet inside.



