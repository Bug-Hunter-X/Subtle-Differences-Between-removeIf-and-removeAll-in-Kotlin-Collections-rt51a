# Subtle Differences Between removeIf and removeAll in Kotlin Collections

This repository demonstrates a subtle difference in behavior between the `removeIf` and `removeAll` functions when used with mutable lists and sets in Kotlin.  While both functions aim to remove elements based on a predicate, their implementation details lead to slightly different outcomes.

The `bug.kt` file showcases this difference with examples using both mutable lists and mutable sets.  The `bugSolution.kt` file provides clarifications and best practices to avoid unexpected behavior.

**Key Observations:**

* The difference is primarily noticeable in how they handle elements during iteration.
* Understanding this difference is crucial for writing robust and predictable code when working with collections.

This example is useful for highlighting a common area of confusion for Kotlin developers working with collections.