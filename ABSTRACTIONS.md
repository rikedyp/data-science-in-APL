# Abstractions, Frameworks and Direct Expression
These investigations raise questions about approaches to problem solving in APL and what is "the APL way".

Often, the performance of intuitive or well-known algorithms (especially the so-called "scalar looping" algorithms) perform poorly in interpreted APL. Some level of abstraction offers the possibility of drop-in replacements using more performant compiled code (for example, [ChrisMoller/mtx](https://github.com/ChrisMoller/mtx) and [Dyalog/math](https://github.com/dyalog/math)).

On the other hand, one of the key tenets of APL is the use of direct expression and subordination of detail over conventional abstraction. This is borne out in the core notation, made extensible by tacit programming constructs, and explored deeply in the [co-dfns project](https://github.com/Co-dfns/).

It is interesting to note Dyalog's "idioms" (recognised set spellings) seem to straddle the line by providing expressions of "raw code" that are executed using special code. Marshall had suggested thunks as a doorway to improved performance for direct APL expressions before going on to create the compiled BQN language.

Then, alongside this, is the Big Question of [what is a primitive?](https://mlochbaum.github.io/BQN/commentary/primitive.html).
