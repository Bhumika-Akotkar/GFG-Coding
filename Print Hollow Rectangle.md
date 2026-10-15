## 01. Print Hollow Rectangle

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/hollow-rectangle-or-square/1)

### Problem Description

**Task:** Given two integers n and m, print a hollow rectangle pattern consisting of n rows and m columns using '*' character. Examples:Input: n = 3, m = 5Output:****** ******Explanation: It's a hollow rectangle with 3 rows and 5 columns.Input: n = 4, m = 3Output:**** ** * ***Explanation: It's a hollow rectangle with 4 rows and 3 columns.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(n * m)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-15 20:33:27
- **Status:** Correct
- **Marks:** 1

```cpp
class Solution {
  public:
    void printHollowRectangle(int n, int m) {
        // code here
        for(int i =0;i<n;i++){
            for(int j=0;j<m;j++){
                if(i==0 || i==n-1||j==0 || j==m-1){
                    cout<<"*";
                }
                else{
                    cout<<" ";
                }
            }
             cout<<endl;
        }
    }
};
```

*Generated on: 15/10/2026, 20:33:58*