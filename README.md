# PHP Loose Comparison Pitfall: '0' == false

This repository demonstrates a common pitfall in PHP programming related to loose comparison using the `==` operator. The code example shows how comparing the string '0' with the boolean `false` results in unexpected equality due to PHP's type juggling behavior.  This can lead to logic errors and hard-to-debug issues in your applications.

## Solution
The recommended approach is to always use strict comparison (`===`) when comparing values in PHP to prevent unexpected type coercion. This ensures that both the value and the type are compared, avoiding the pitfalls of loose comparison.

## How to Run
1. Clone this repository.
2. Navigate to the project directory in your terminal.
3. Run `php bug.php` to observe the unexpected behavior.  Then run `php bugSolution.php` to see the corrected version. 