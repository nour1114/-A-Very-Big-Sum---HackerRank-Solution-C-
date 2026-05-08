# A Very Big Sum - HackerRank Solution (C++)

This repository contains my C++ solution for the HackerRank problem:

🔹 A Very Big Sum

The solution demonstrates:
- Working with arrays/vectors
- Using `long long` for large integer sums
- Basic iteration and accumulation logic in C++

## Concepts Used
- C++
- Vectors
- Loops
- Problem Solving

## Solution
```cpp
long long aVeryBigSum(vector<long> ar) {
    long long sum = 0;

    for (int i = 0; i < ar.size(); i++) {
        sum += ar[i];
    }

    return sum;
}
