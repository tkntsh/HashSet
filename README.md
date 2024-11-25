# Find Duplicates in an Array

This Java program demonstrates how to identify duplicate elements in an array using a `HashSet`. It provides an efficient solution for detecting duplicates by leveraging the properties of sets, which do not allow duplicate values.

---

## File

### **FindDuplicates.java**
- **Purpose**: Identifies duplicate elements in an array of integers.
- **Features**:
  - Iterates through an array of integers.
  - Uses a `HashSet` to track seen elements.
  - Adds duplicates to a separate `HashSet` for output.
- **Key Concepts**:
  - **HashSet**: A collection that stores unique elements and provides efficient operations for adding and checking membership.
  - **Algorithm**:
    1. Iterate through the array.
    2. Attempt to add each element to a `HashSet` of seen elements.
    3. If adding fails (element already exists), it is added to the `duplicates` set.

#### Example Input
```java
int[] numbers = {1, 2, 3, 4, 5, 2, 3};
