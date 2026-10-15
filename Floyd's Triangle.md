## 01. Floyd's Triangle

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/floyds-triangle1222/1)

### Problem Description

**Task:** Given a number n, print Floyd's triangle with n lines.Floyd’s Triangle is a pattern of consecutive natural numbers arranged in rows, where the i-th row contains i numbers.Examples:Input: n = 4

#### Examples

##### Example 1

- **Explanation:** The triangle has 4 rows, and each row i contains i numbers.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(n^2)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (2)

#### Solution 1 (C++)

- **Submitted:** 2026-10-15 20:16:32
- **Status:** Correct
- **Marks:** 0

```cpp
class Solution {
  public:
    void printFloydTriangle(int n) {
        int count=1;// code here
        for(int i= 0;i<n;i++){
            for(int j =0;j<=i;j++){
                cout<<count<<" ";
                count++;
            }
            cout<<endl;
        }
    }
};
```

#### Solution 2 (C++)

- **Submitted:** 2026-10-15 20:16:17
- **Status:** Correct
- **Marks:** 1

```cpp
class Solution {
  public:
    void printFloydTriangle(int n) {
        int count=1;// code here
        for(int i= 0;i<n;i++){
            for(int j =0;j<=i;j++){
                cout<<count<<" ";
                count++;
            }
            cout<<endl;
        }
    }
};
```

*Generated on: 15/10/2026, 20:17:01*