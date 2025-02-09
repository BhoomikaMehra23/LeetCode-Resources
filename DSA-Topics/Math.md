# 📌 Math & Number Theory 🚀  

This section covers fundamental **math concepts** required for solving coding problems, including **GCD, modular arithmetic, prime numbers, and combinatorics**.  

---

## 📖 Topics Covered  
✔ **Greatest Common Divisor (GCD) & Least Common Multiple (LCM)**  
✔ **Modular Arithmetic & Modulo Properties**  
✔ **Prime Numbers & Sieve of Eratosthenes**  
✔ **Combinatorics & Factorial Calculations**  
✔ **Number Theory Tricks for Competitive Programming**  

---

## 🔹 1. Greatest Common Divisor (GCD) & Least Common Multiple (LCM)  

📌 **Concept:**  
- **GCD (Greatest Common Divisor):** Largest number that divides two numbers without a remainder.  
- **LCM (Least Common Multiple):** Smallest number that is a multiple of two numbers.  

📌 **Formulae:**  
- `GCD(a, b) = GCD(b, a % b)` → **(Euclidean Algorithm)**  
- `LCM(a, b) = (a * b) / GCD(a, b)`  

📌 **LeetCode Problems:**  
✅ [LC 1979 - Find Greatest Common Divisor of an Array](https://leetcode.com/problems/find-greatest-common-divisor-of-an-array/)  
✅ [LC 1445 - Find Minimum Number of Fibonacci Terms with GCD](https://leetcode.com/problems/find-minimum-number-of-fibonacci-terms-with-gcd/)  

---

## 🔹 2. Modular Arithmetic & Modulo Properties  

📌 **Concept:**  
- Modulo (`%`) finds the remainder when dividing two numbers.  
- Used in **big number computations, cryptography, and modulo inverses**.  

📌 **Properties:**  
✔ `(a + b) % m = [(a % m) + (b % m)] % m`  
✔ `(a * b) % m = [(a % m) * (b % m)] % m`  
✔ **Fermat’s Theorem:** `a^(m-1) ≡ 1 (mod m)` (used for modular inverses when `m` is prime)  

📌 **LeetCode Problems:**  
✅ [LC 1922 - Count Good Numbers](https://leetcode.com/problems/count-good-numbers/)  
✅ [LC 372 - Super Pow (Efficient Modulo Exponentiation)](https://leetcode.com/problems/super-pow/)  

---

## 🔹 3. Prime Numbers & Sieve of Eratosthenes  

📌 **Concept:**  
- A **prime number** is only divisible by **1 and itself**.  
- **Sieve of Eratosthenes** is an efficient way to find all primes up to `N` in `O(N log log N)`.  

📌 **LeetCode Problems:**  
✅ [LC 204 - Count Primes](https://leetcode.com/problems/count-primes/)  
✅ [LC 1175 - Prime Arrangements](https://leetcode.com/problems/prime-arrangements/)  

---

## 🔹 4. Combinatorics & Factorial Calculations  

📌 **Concept:**  
- **Factorial (`n!`)**: `n! = n × (n-1) × ... × 1`  
- **nCr (Combination Formula)**: `nCr = n! / (r! × (n-r)!)`  
- Efficient computation using **modular inverses**.  

📌 **LeetCode Problems:**  
✅ [LC 2312 - Selling Pieces of Wood (Combinations)](https://leetcode.com/problems/selling-pieces-of-wood/)  
✅ [LC 1359 - Count All Valid Pickup and Delivery Options](https://leetcode.com/problems/count-all-valid-pickup-and-delivery-options/)  

---

## 🔹 5. Number Theory Tricks  
📌 **Common Tricks Used in LeetCode:**  
✅ **Bit Manipulation for Checking Powers of 2**  
✅ **Fibonacci with Matrix Exponentiation**  
✅ **Chinese Remainder Theorem (for complex modular problems)**  

---

### 🚀 **Next Steps**  
1️⃣ **Practice the linked questions**  
2️⃣ **Implement GCD, Sieve, Modular Arithmetic in Java**  
3️⃣ **Move to Advanced Topics like Euler’s Totient Function & Number Bases**  

---

⭐ **Star this repo** if you found it helpful! 🚀  

