# CSS `calc()` Gotchas

This repository demonstrates some uncommon issues that can arise when using the `calc()` function in CSS.  Specifically, it addresses:

* **Operator precedence:** The order of operations in `calc()` expressions needs careful attention.
* **Unit consistency:**  All values within a `calc()` expression must use compatible units.
* **Nested `calc()`:**  While possible, excessively nested `calc()` can decrease readability and debugging ease.
* **Missing Units:** Missing units result in unexpected behavior.

The `bug.css` file shows examples of these errors, while `bugSolution.css` provides corrected versions.