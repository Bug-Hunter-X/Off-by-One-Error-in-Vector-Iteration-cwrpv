# Off-by-One Error in Vector Iteration

This example demonstrates a common off-by-one error in C++ when iterating over a `std::vector`.  The error occurs because the loop condition `i <= vec.size()` attempts to access an element beyond the valid range of the vector, leading to undefined behavior. The correct condition should be `i < vec.size()`. 

**bug.cpp** shows the erroneous code, and **bugSolution.cpp** provides the corrected version. 