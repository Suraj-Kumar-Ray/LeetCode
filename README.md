# LeetCode — Java Solutions

My Data Structures & Algorithms practice, one problem per folder. **400+ problems solved** in total
on [LeetCode](https://leetcode.com/) — this repo keeps the ones worth revisiting with clean,
readable Java.

[![Language](https://img.shields.io/badge/language-Java-007396?logo=openjdk&logoColor=white)](https://github.com/Suraj-Kumar-Ray/LeetCode)
[![Problems](https://img.shields.io/badge/problems%20solved-400%2B-6366f1)](https://github.com/Suraj-Kumar-Ray/LeetCode)

## How this repo is organised

Every folder is `<number>-<slug>` and holds the solution plus a short note on the approach and
its time/space complexity:

```
0001-two-sum/
  0001-two-sum.java   # the solution
  README.md           # approach + complexity
```

## Solved so far

| # | Problem | Difficulty | Approach |
|---|---------|------------|----------|
| 0001 | [Two Sum](https://leetcode.com/problems/two-sum/) | Easy | Hash map, one pass — O(n) |
| 0002 | [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/) | Medium | Linked list traversal with carry |
| 0026 | [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Easy | Two pointers, in place |
| 0027 | [Remove Element](https://leetcode.com/problems/remove-element/) | Easy | Two pointers, in place |
| 0088 | [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | Easy | Merge from the back — O(m+n) |
| 0485 | [Max Consecutive Ones](https://leetcode.com/problems/max-consecutive-ones/) | Easy | Single pass counter |
| 0977 | [Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) | Easy | Two pointers from both ends |
| 1295 | [Find Numbers with Even Number of Digits](https://leetcode.com/problems/find-numbers-with-even-number-of-digits/) | Easy | Digit count / string length |
| 1346 | [Check If N and Its Double Exist](https://leetcode.com/problems/check-if-n-and-its-double-exist/) | Easy | Hash set lookup |

## Running a solution

Every file is a plain Java class — no build tool needed:

```bash
cd 0001-two-sum
javac 0001-two-sum.java
java 0001
```

---

More about me: [portfolio](https://suraj-portfolio-wjpt.onrender.com) ·
[LinkedIn](https://linkedin.com/in/suraj-kumar-507119203)
