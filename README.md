# Blockchain Developer Bootcamp Final Project

## Multi-party atomic swaps

A dAPP that allows an arbitrary number of parties to perform an atomic swap.

1. N users (e.g. 3) signal their willingness to exchange tokens (e.g. User 1 wants to exchange `outgoingToken1` for `incomingToken1`, User 2 wants to exchange `outgoingToken2` for `incomingToken2`, User 3 wants to exchange `outgoingToken3` for `incomingToken3`).
2.  Let's suppose that there is a "triangular" match for these 3 orders, meaning that `outgoingToken1 = incomingToken2`, `outgoingToken2 = incomingToken3` and `outgoingToken3 = incomingToken1`.
3.  The dAPP matches these 3 orders so that everyone can perform their desired trade, which wouldn't be possible in 2-party atomic swaps.
