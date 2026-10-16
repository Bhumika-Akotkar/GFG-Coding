## 01. Factorial

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/factorial5739/1)

### Problem Description

**Task:** Given a positive integer, n. Find the factorial of n.Examples :Input: n = 5

#### Examples

##### Example 1

- **Output:**
```text
24
```
- **Explanation:** 1 x 2 x 3 x 4 = 24

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(n)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-16 12:38:01
- **Status:** Correct
- **Marks:** 1

```cpp
class Solution {
  public:
    int factorial(int n) {
        int fac=1;
        // code here
       
        for(int i=1;i<=n;i++){
            fac*=i;
            
        }
        return fac;
    }
};
```

*Generated on: 16/10/2026, 12:38:40*