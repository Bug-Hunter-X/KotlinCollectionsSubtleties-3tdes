This repository showcases a subtle but important difference in how the `removeIf` function behaves with various Kotlin collection types (List, Map, Set).  The `bug.kt` file demonstrates the unexpected behavior with Maps. The `bugSolution.kt` file demonstrates the correct approach for handling this scenario.  The issue stems from modifying a collection while iterating through it using its iterator. Please see the code examples for details.