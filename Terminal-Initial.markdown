# Terminal object

## Definition

A terminal object is an object where every object in its category has a *unique* morphism to it.

(unique is important)

Terminal object T in C: ∀x ∈C ∃! x -> T

Universal property: ∀x ∈C ∃! x -> T

Aka final.

## Examples

### Set

1-element sets are the terminal object

But there are a bunch of 1-element sets! Aren't they *all* terminal objects? Are there more than one terminal objects? Doesn't it have to be unique?

It is unique up to unique isomorphism (canonical isomorphism)

### Group

Trivial group

### Topological spaces

One-point space

### Poset [a -> b means a < b]

The maximum

## Proof that they're unique

### Lemma:

Terminal objects in C are unique up to unique isomorphism.

ie if T and T' are terminal objects in C then there exists a unique isomorphism T -> T'
