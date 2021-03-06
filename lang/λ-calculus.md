# λ-calculus

## Untyped λ-calculus

## Simply-typed λ-calculus


> As mentioned, Church’s first use of lambda calculus was to encode formulas of logic, but this had to be abandoned because it led to inconsistency. The failure arose for a reason related to Russell’s paradox, namely that the system allowed a predicate to act on itself, and so Church adapted a solution similar to Russell’s, that of classifying terms according to types. Church’s simply-typed lambda calculus ruled out self-application, permitting lambda calculus to support a consistent logical formulation [10].

> Whereas self-application in Russell’s logic leads to paradox, self-application in Church’s untyped lambda calculus leads to non-terminating computations. Conversely, Church’s simply-typed lambda calculus guarantees every term has a normal form, that is, corresponds to a computation that halts.

> The two applications of lambda calculus, to represent computation and to represent logic, are in a sense mutually exclusive. If a notion of computation is powerful enough to represent any effectively calculable procedure, then that notion is not powerful enough to solve its own Halting Problem: there is no effectively calculable procedure to determine whether a given effectively calculable procedure terminates. However, the consistency of Church’s logic based on simply-typed lambda calculus depends on every term having a normal form.

> Untyped lambda calculus or typed lambda calculus with a construct for general recursion (sometimes called a fixpoint operator) permits the definition of any effectively computable function, but have a Halting Problem that is unsolvable. Typed lambda calculi without a construct for general recursion have a Halting Problem that is trivial—every program halts!—but cannot define some effectively computable functions. Both kinds of calculus have their uses, depending on the intended application.
