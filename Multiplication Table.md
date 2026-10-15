## 01. Multiplication Table

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/multiplication-table/1)

### Problem Description

**Task:** Given a number n, print the multiplication table from 1 to 10 for n in a single line, separated by spaces.

#### Examples

##### Example 1

- **Input:**
```text
n = 9Output: 9 18 27 36 45 54 63 72 81 90
```

##### Example 2

- **Input:**
```text
n = 2Output: 2 4 6 8 10 12 14 16 18 20
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-15 19:28:57
- **Status:** Correct
- **Marks:** 0

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin >> n;
    int i=1;
    
    while(i<=10){
    cout<<n*i<<" " ;
        i++;

    }
   
   

    // code here
    

    return 0;
}
```

*Generated on: 15/10/2026, 20:41:46*