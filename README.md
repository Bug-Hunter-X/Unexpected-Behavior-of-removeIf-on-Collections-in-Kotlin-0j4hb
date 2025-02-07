# Unexpected removeIf Behavior in Kotlin Collections

This repository demonstrates a potential source of confusion for Kotlin developers: the `removeIf` function's in-place modification of collections. While generally efficient, this behavior can lead to unexpected results if not carefully considered.

The `bug.kt` file shows examples using `removeIf` with `List`, `Set`, and `Map` to illustrate how it modifies the original collections.

The `bugSolution.kt` (if provided) may offer alternative approaches to avoid in-place modification or better handle the behavior.

This is a common yet subtle issue, especially for developers transitioning to Kotlin from languages with more explicit immutable collection handling.