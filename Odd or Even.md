## 01. Odd or Even

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/odd-or-even3618/1)

### Problem Description

**Task:** Given a positive integer n, find if it is odd or even. Return true if the number is even else false.Examples:Input: n = 15

#### Examples

##### Example 1

- **Output:**
```text
false
```
- **Explanation:** The number is not divisible by 2, Odd number.Input: n = 44Output: trueExplanation: The number is divisible by 2, Even number.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-15 19:53:00
- **Status:** Correct
- **Marks:** 2

```cpp
class Solution {
  public:
    bool isEven(int n) {
        // code here
        if(n%2==0){
            return true;
        }else{
            return false;
        }
    }
};
```

*Generated on: 15/10/2026, 20:43:33*