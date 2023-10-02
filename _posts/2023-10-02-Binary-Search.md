---
title: Binary Search
author: Bhoomeendra 
date: 2023-10-02
category: Jekyll
layout: post
---

## Problems
### [852. Peak Index in a Mountain Array](https://leetcode.com/problems/peak-index-in-a-mountain-array/description/)

Given a mountain array we are supposed to find the peak elements index. This is interesting problem because the sorted nature of the array is preserved but the elements of the array are roated. Now to inforce that in the binary seach we will it in such a manner. Let say we pick a random elm from the array for it to be the peak it has to be greater that its adjcent elements. the other two choices are we see a decreasing pattern around the elm if so then the peak is definalty on the left side of the array and if we see a increasing pattern then the peak is on the right side of the array.

### 

