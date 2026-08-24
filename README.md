# 🔢 LeetCode 18 - 4Sum

## 📌 Problem

Given an integer array `nums` and an integer `target`, return all unique quadruplets `[nums[a], nums[b], nums[c], nums[d]]` such that:

`nums[a] + nums[b] + nums[c] + nums[d] = target`

The solution must not contain duplicate quadruplets.

## 💡 Approach

Use **Sorting + Two Pointers**.

1. Sort the array.
2. Fix the first two elements using two loops.
3. Use two pointers to find the remaining two elements.
4. Compare their sum with the target.
5. Move the pointers accordingly.
6. Skip duplicate values to avoid duplicate quadruplets.

## 🧪 Example

**Input:**
`nums = [1,0,-1,0,-2,2]`
`target = 0`

**Output:**
`[[-2,-1,1,2], [-2,0,0,2], [-1,0,0,1]]`

### Explanation

Each quadruplet has a sum equal to `0`.

* `-2 + -1 + 1 + 2 = 0`
* `-2 + 0 + 0 + 2 = 0`
* `-1 + 0 + 0 + 1 = 0`

## ⏱️ Complexity

* **Time Complexity:** O(n³)
* **Space Complexity:** O(1), excluding the output array.

## 🏷️ LeetCode Details

* **Problem:** 4Sum
* **Problem Number:** 18
* **Difficulty:** Medium
* **Language:** Python

## 🎯 Topics

* Arrays
* Sorting
* Two Pointers
* Searching

## 👩‍💻 Author

**Nandhini**
