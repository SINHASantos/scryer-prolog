# Scryer Prolog

```
?- append("Hello, ", X, "Hello, Scryer Prolog!").
   X = "Scryer Prolog!".
```

![scryer](scryer.png){width=128 style=float:right;} [Scryer Prolog](https://github.com/mthom/scryer-prolog) is a free software ISO Prolog system intended to be an industrial
strength production environment *and* a testbed for bleeding edge research in
logic and constraint programming.

Some of the Scryer Prolog features are:

* ISO standard compliant
* Integrated constraint programming libraries: [clp(B)](/clpb.html), [clp(Z)](/clpz.html).
* [Definite Clause Grammars](/dcgs.html)
* Coroutining support ([`dif/2`](/dif.html), [`freeze/2`](/freeze.html), ...)
* [Tabling and SLG resolution](/tabling.html)
* Compact string representation
* Network libraries ([TCP sockets](/sockets.html), [HTTP server](/http/http_server.html), [HTTP client](/http/http_open.html), ...)
* [Cryptographical predicates](/crypto.html)
* WAM based engine, cross-platform made in Rust
* _and more..._

## What is Prolog?

Prolog is a logic programming language created by [Alain Colmerauer](https://en.wikipedia.org/wiki/Alain_Colmerauer) and [Robert Kowalski](https://en.wikipedia.org/wiki/Robert_Kowalski) in 1972.
The idea behind Prolog is try to express a task in language similar to First Order Logic.
Prolog systems include _unification_ and _non-determinism_ as key concepts upon which we build programs.

A Prolog program is made up of predicates which define a relation between its arguments. A predicate
is made from clauses. A clause can be either a fact or a rule. There's also a toplevel, which we
can use to ask and reason about our task.

It's still to this day one of the best examples and one of the most popular languages in the field
of logic programming. That's because Prolog allows us to elegantly solve many tasks with short and
general programs.

If you want a more detailed description of Prolog, check [A Tour of Prolog](https://www.youtube.com/watch?v=8XUutFBbUrg).

If you want to learn more about Prolog history, check the videos [l'Aventure Prolog](https://www.youtube.com/watch?v=74Ig_QKndvE) and [50 years of Prolog and beyond](https://prologyear.logicprogramming.org/videos/PrologDay_Session_1_talk.mp4).

## Where can I learn Prolog?

There are a lot of classical Prolog books. Those books can teach you the basics of Prolog. Some
examples are: _The Art of Prolog (Shapiro)_, _Programming in Prolog (Clocksin, Mellish)_ and _The Craft
of Prolog (O'Keefe)_. However, most of them are not updated to _modern_ Prolog.
We recommend _[The Power of Prolog (Markus Triska)](https://www.metalevel.at/prolog)_ for modern Prolog. For reference about
the builtin Prolog modules and libraries in Scryer, check the documentation site. It's this!

## Downloads

The latest version of Scryer Prolog is *0.9.1*. And it's already useful for lots of tasks.

Scryer Prolog can be compiled from source, instructions are on the [GitHub README](https://github.com/mthom/scryer-prolog). It runs on Linux, macOS and Windows. Other operating systems may work but they're not regularly tested.

If you're in Linux, maybe your distribution already has an Scryer Prolog package.

There's also a [Docker image](https://github.com/mthom/scryer-prolog#docker-install) available.

## Support and discussions

If Scryer Prolog crashes or yields unexpected errors, consider filing
an [issue](https://github.com/mthom/scryer-prolog/issues).

To get in touch with the Scryer Prolog community, participate in
[discussions](https://github.com/mthom/scryer-prolog/discussions)
or visit our #scryer IRC channel on [Libera](https://libera.chat)!