# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java when iterating through arrays.  The error arises from incorrectly handling the loop termination condition, leading to an `ArrayIndexOutOfBoundsException`.

**Buggy Code:** The `BuggyArray.java` file contains the code with the error.  The loop attempts to access an index that is outside the valid range of the array.

**Solution:** The `FixedArray.java` file provides the corrected code. The loop condition is modified to avoid accessing the index beyond the array's bounds.