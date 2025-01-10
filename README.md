# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java bug: an `ArrayIndexOutOfBoundsException` caused by an off-by-one error in a `for` loop.

The `BuggyArray.java` file contains the buggy code.  The loop attempts to access an index one past the end of the array, resulting in the exception.  The corrected code is in `FixedArray.java`.