## 01. The Else if Statement

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/the-else-if-statement/1)

### Problem Description

**Task:** Given a number, you have to use if, else if, else conditional statements according to the following:if number is greater than 100: Print "Big" (without quotes)else if number is smaller than 10: Print "Small" (without quotes)else: Print "Number" (without quotes)

> **Note:** Ensure that the output includes a newline after every print statement.

#### Examples

##### Example 1

- **Input:**
```text
number = 9
```
- **Output:**
```text
Small
```
- **Explanation:** Here, the else if condition will work as 9 is smaller than 10.

##### Example 2

- **Input:**
```text
number = 101
```
- **Output:**
```text
Big
```
- **Explanation:** 101 is greater than 100, so our if statement works and we print Big.

##### Example 3

- **Input:**
```text
number = 30
```
- **Output:**
```text
Number
```
- **Explanation:** 30 is neither greater than 100, nor smaller than 10, so the else statement works here.

#### Constraints

- **1.** `1 ≤ number ≤ 1000`

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (C++)

- **Submitted:** 2026-10-15 19:43:29
- **Status:** Correct
- **Marks:** 1

```cpp
void utility(int number) {
    if(number>100){
        cout<<"Big"<<endl;
    }
    else if(number<10){
        cout<<"Small"<<endl;
    }
    else{
        cout<<"Number"<<endl;
    }
    // Write the if, else if, else statements below
}
```

*Generated on: 15/10/2026, 20:42:46*