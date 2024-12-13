# Uncommon CSS `calc()` Errors and Solutions

This repository demonstrates some uncommon errors that can occur when using the `calc()` function in CSS, along with their solutions.  The `calc()` function is powerful, but requires careful attention to detail.

**Common Issues:**

* **Missing spaces:** Operators in `calc()` must be surrounded by spaces (e.g., `width: calc(100% - 10px)`).
* **Incorrect units:** Ensure consistent units throughout the calculation (e.g., don't mix `px` and `%`).
* **Unsupported operations:**  `calc()` has limitations; some mathematical operations are not supported.

**Example Errors and Solutions:**  See the `bug.css` and `bugSolution.css` files for code samples.