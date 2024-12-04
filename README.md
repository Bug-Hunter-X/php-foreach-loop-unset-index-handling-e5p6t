# PHP Foreach Loop with Unset() Gotcha

This example demonstrates a subtle but important issue when using the `unset()` function within a `foreach` loop in PHP.  Modifying the array being iterated over during the loop can lead to unexpected index skipping, resulting in data loss or incorrect results.

The `bug.php` file contains the problematic code.  The `bugSolution.php` file offers a corrected approach.