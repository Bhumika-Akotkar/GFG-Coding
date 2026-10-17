## 01. Sum of Natural Number Cubes

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/sum-of-first-n-terms5843/1)

### Problem Description

**Task:** Given an integer n, calculate the sum of series 1³ + 2³ + 3³ + 4³ + … till n-th term.Examples:Input: n = 5

#### Examples

##### Example 1

- **Output:**
```text
784
```
- **Explanation:** 1³ + 2³ + 3³ + 4³ + 5³ + 6³ + 7³ = 784

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-17 20:58:10
- **Status:** Correct
- **Marks:** 1

```cpp
class Solution {
  public:
    int sumOfSeries(int n) {
        int sum=0;
        // code here
        for(int i=1;i<=n;i++){
            sum+=i*i*i;
        }
        return sum;
    }
   
    
};
```

*Generated on: 17/10/2026, 20:58:39*