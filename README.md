# 🎯 GeeksforGeeks 160 Days - Coding Challenge

Welcome to my repository for the **GeeksforGeeks 160 Days Coding Challenge**! 🚀

Here, I document my daily progress, problem solutions, and key learnings as I solve algorithmic problems consistently over 160 days.

---

## 🚀 Progress Tracker

| Progress | Status |
| :--- | :--- |
| 🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢🟢... | **Day 25 / 160 Completed** |
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
| **Day 12** | Maximum Circular Subarray Sum | [Code](./Day%2012%20-%20Maximum%20Circular%20Subarray%20Sum) | $O(N)$ | ✅ Completed |
| **Day 13** | Smallest Positive Missing Number | [Code](./Day%2013%20-%20Smallest%20Positive%20Missing%20Number) | O(N) | ✅ Completed |
| **Day 14** | Implement Atoi | [Code](./Day%2014%20-%20Implement%20Atoi) | O(N) | ✅ Completed |
| **Day 15** | Add Binary Strings | [Code](./Day%2015%20-%20Add%20Binary%20Strings) | O(N) | ✅ Completed |
| **Day 16** | Anagram | [Code](./Day%2016%20-%20Anagram) | O(N) | ✅ Completed |
| **Day 17** | Non Repeating Character | [Code](./Day%2017%20-%20Non%20Repeating%20Character) | O(N) | ✅ Completed |
| **Day 18** | Search Pattern | [Code](./Day%2018%20-%20Search%20Pattern) | O(N) | ✅ Completed |
| **Day 19** | Min Chars to Add for Palindrome | [Code](./Day%2019%20-%20Min%20Chars%20to%20Add%20for%20Palindrome) | O(N) | ✅ Completed |
| **Day 20** | Strings Rotations of Each Other | [Code](./Day%2020%20-%20Strings%20Rotations%20of%20Each%20Other) | O(N) | ✅ Completed |
| **Day 21** | Sort 0s, 1s and 2s | [Code](./Day%2021%20-%20Sort%200s%2C%201s%20and%202s) | O(N) | ✅ Completed |
| **Day 22** | Find H-Index | [Code](./Day%2022%20-%20Find%20H-Index) | O(N log N) | ✅ Completed |
| **Day 23** | Count Inversions | [Code](./Day%2023%20-%20Count%20Inversions) | O(N log N) | ✅ Completed |
| **Day 24** | Overlapping Intervals | [Code](./Day%2024%20-%20Overlapping%20Intervals) | O(N log N) | ✅ Completed |
| **Day 25** | Insert Interval | [Code](./Day%2025%20%E2%80%94%20Insert%20Interval) | O(N) | ✅ Completed |
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
* **Day 12:** Calculated the maximum circular subarray sum in $O(N)$ time and $O(1)$ space by comparing the maximum normal subarray sum (using Kadane's algorithm) with the total sum minus the minimum subarray sum.
* **Day 13:** Placed each positive number in its correct 1-based index position (`arr[i]` at `arr[i] - 1`) to find the first missing positive integer in $O(N)$ time and $O(1)$ auxiliary space.
* **Day 14:** Converted a string to a 32-bit signed integer by handling leading spaces, signs (+/-), non-digit characters, and 32-bit integer overflow/underflow boundaries in $O(N)$ time complexity.
* **Day 15:** Added two binary strings from right to left using a two-pointer approach and a carry variable, ensuring leading zeros are trimmed from the final result in $O(N)$ time and space.
* **Day 16:** Checked if two strings are anagrams of each other by maintaining a frequency count array of size 26 for lower-case English characters, incrementing for the first string and decrementing for the second string in $O(N)$ time and $O(1)$ auxiliary space.
* **Day 17:** Counted character frequencies using a hash map or frequency array in $O(N)$ time, then made a second pass over the string to find the first character with a frequency of 1.
* **Day 18:** Implemented the Knuth-Morris-Pratt (KMP) pattern matching algorithm by precomputing the Longest Prefix Suffix (LPS) array, enabling search in $O(N + M)$ time complexity.
* **Day 19:** Computed the Longest Prefix Suffix (LPS) array of the string concatenated with its reverse (separated by a special character) to find the longest palindromic prefix in $O(N)$ time, determining the minimum characters needed to make the string a palindrome.
* **Day 20:** Checked if string $s2$ is a rotation of $s1$ in $O(N)$ time by concatenating $s1$ with itself ($s1 + s1$) and searching for $s2$ within it using the KMP algorithm (or string search).
* **Day 21:** Sorted an array containing only 0s, 1s, and 2s using frequency counting, rebuilding the array in ascending order in O(N) time and O(1) auxiliary space.
* **Day 22:** Calculated the H-Index by sorting the citations array in descending order and finding the largest value $h$ where the paper count exceeds or equals $h$, running in $O(N \log N)$ time and $O(1)$ auxiliary space (or $O(N)$ time using frequency counting/bucket sort).
* **Day 23:** Used a modified Merge Sort algorithm to count array inversions in $O(N \log N)$ time and $O(N)$ space by adding the remaining elements in the left subarray whenever an element from the right subarray is smaller.
* **Day 24:** Sorted intervals by their starting times and merged overlapping ranges in a single pass by updating the end time of the current interval, running in O(N log N) time due to sorting and O(1) extra space (excluding output space).
* **Day 25:** Inserted a new interval into a non-overlapping sorted interval list and merged overlapping intervals in a single pass in $O(N)$ time and $O(1)$ auxiliary space (excluding output array).
