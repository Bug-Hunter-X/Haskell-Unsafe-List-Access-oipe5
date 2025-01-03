# Haskell Unsafe List Access

This repository demonstrates a common error in Haskell: unsafe list access.  Attempting to access elements of a list using an index that is out of bounds (less than 0 or greater than or equal to the length of the list) will cause a runtime exception.  This example shows how this error can occur and how to safely handle it.

**bug.hs:** Contains the code that demonstrates the unsafe access.

**bugSolution.hs:**  Shows how to safely access list elements using pattern matching or other safe Haskell techniques. 

This example is useful for learning safe Haskell programming practices and for understanding how to avoid runtime errors stemming from incorrect list manipulation.