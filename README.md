# 🎯 GeeksforGeeks 160 Days - Coding Challenge

Welcome to my repository for the **GeeksforGeeks 160 Days Coding Challenge**! 🚀

Here, I document my daily progress, problem solutions, and key learnings as I solve algorithmic problems consistently over 160 days.

---

## 🚀 Progress Tracker

| Progress | Status |
| :--- | :--- |
| 🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢... | **Day 11 / 160 Completed** |

---

## 📅 Daily Problem Log

### 🔹 Week 1: Arrays & Basic Algorithms

| Day | Topic / Problem Name | Solution | Complexity | Status |
| :---: | :--- | :---: | :---: | :---: |
| **Day 01** | Second Largest Element | [Code](./Day%2001%20-%20Second%20Largest%20Element) | O(N) | ✅ Completed |
| **Day 02** | Move All Zeroes to End | [Code](./Day%2002%20-%20Move%20All%20Zeroes%20to%20End) | O(N) | ✅ Completed |
| **Day 03** | Reverse an Array | [Code](./Day%2003%20-%20Reverse%20an%20Array) | O(N) | ✅ Completed |
| **Day 04** | Rotate Array | [Code](./Day%2004%20-%20Rotate%20Array) | O(N) | ✅ Completed |
| **Day 05** | Next Permutation | [Code](./Day%2005%20-%20Next%20Permutation/) | O(N) | ✅ Completed |
| **Day 06** | Majority Element II | [Code](./Day%2006%20-%20Majority%20Element/) | O(N) | ✅ Completed |
| **Day 07** | Stock Buy and Sell – Multiple Transaction | [Code](./Day%2007%20-%20Stock%20Buy%20and%20Sell) | O(N) | ✅ Completed |
| **Day 08** | Stock Buy and Sell – Max One Transaction Allowed | [Code](./Day%2008%20-%20Stock%20Buy%20and%20Sell) | O(N) | ✅ Completed |
| **Day 09** | Minimize the Heights II | [Code](./Day%2009%20-%20Minimize%20the%20Heights%20II) | O(N log N) | ✅ Completed |
| **Day 10** | Kadane's Algorithm | [Code](./Day%2010%20-%20Kadane's%20Algorithm) | O(N) | ✅ Completed |
| **Day 11** | Maximum Product Subarray | [Code](./Day%2011%20-%20Maximum%20Product%20Subarray) | O(N) | ✅ Completed |

---

## 💡 Key Learnings & Takeaways

* **Day 01:** Learned how to find the second largest element in a single pass without sorting, keeping time complexity strictly O(N).
* **Day 02:** Shifted non-zero elements forward maintaining order, filling remaining places with zeros in O(N) time.
* **Day 03:** Reversed the array using two-pointer approach in O(N) time and O(1) space.
* **Day 04:** Rotated the array by $d$ positions using the reversal algorithm in O(N) time and O(1) auxiliary space.
* **Day 05:** Found the next lexicographical permutation in O(N) time by locating the pivot element, swapping it with the next greater element, and reversing the trailing subarray.
* **Day 06:** Used Boyer-Moore’s Voting Algorithm to find elements appearing more than $\lfloor N/3 \rfloor$ times in $O(N)$ time and $O(1)$ space.
* **Day 07:** Maximized profit by adding every positive price difference between consecutive days ($\text{prices}[i] - \text{prices}[i-1]$) in a single $O(N)$ pass.
* **Day 08:** Tracked the minimum buy price while traversing the array to calculate potential profit ($\text{prices}[i] - \text{minPrice}$) and updated the maximum profit in a single $O(N)$ pass with $O(1)$ space.
* **Day 09:** Sorted the array and adjusted elements by $k$, keeping track of minimum and maximum possible values while ensuring no height becomes negative, running in $O(N \log N)$ time.
* **Day 10:** Implemented Kadane's Algorithm to find the maximum subarray sum in a single pass ($O(N)$ time and $O(1)$ space) by resetting current sum to 0 whenever it becomes negative.
* **Day 11:** Tracked both maximum and minimum products at each step to account for negative numbers, achieving an optimal $O(N)$ time and $O(1)$ space solution.
