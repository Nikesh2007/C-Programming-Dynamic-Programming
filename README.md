# C-Programming-Dynamic-Programming
This program calculates the nth Fibonacci number using Dynamic Programming in C.   It applies a bottom-up approach by storing results in an array to avoid recomputation.   Base cases are initialized as F(0) = 0 and F(1) = 1.   The time complexity is O(n) and space complexity is O(n).   This approach is more efficient than simple recursion.
# Fibonacci using Dynamic Programming in C

## 📘 About
This project demonstrates how to compute the Fibonacci sequence using **Dynamic Programming (DP)** in C.  
Instead of the traditional recursive method, which leads to repeated calculations and exponential time,  
this approach stores intermediate results to achieve better performance.

## 🔧 How It Works
1. The program takes an integer `n` as input from the user.  
2. It creates an array `dp[]` of size `n+1` to store the Fibonacci values.  
3. Base cases are initialized: `dp[0] = 0` and `dp[1] = 1`.  
4. Each Fibonacci number is computed iteratively:  
5. Finally, the program prints the nth Fibonacci number (`dp[n]`).  

## ⏱️ Complexity
- **Time Complexity:** O(n)  
- **Space Complexity:** O(n)  

## ✅ Example

## 🚀 Advantages
- Faster than recursive Fibonacci (which is exponential).  
- Avoids stack overflow from deep recursion.  
- Easy to understand and extend for other DP problems.
