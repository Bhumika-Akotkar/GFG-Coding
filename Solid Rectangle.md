## 01. Solid Rectangle

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/solid-rectangle/1)

### Problem Description

**Task:** Given two integers n and m, print a solid rectangle pattern of n rows and m columns using the "*" character.Examples:Input: n = 3, m = 5Output:* * * * ** * * * ** * * * *Explanation: A solid rectangle with 3 rows and 5 columns.Input: n = 4, m = 2Output:* ** ** ** *Explanation: A solid rectangle with 4 rows and 2 columns.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(n * m)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-15 20:21:02
- **Status:** Correct
- **Marks:** 1

```cpp
class Solution {
  public:
    void printSolidRectangle(int n, int m) {
        // code here
        for(int i=0;i<n;i++){
            for(int j =0;j<m;j++){
                cout<<"* ";
            }
            cout<<endl;
        }
    }
};
```

*Generated on: 15/10/2026, 20:21:35*