# 100-DAYS-DSA-AND-LEETCODE

Hi All,
Today on 14th June, 2023, I am starting the DSA in Java along with Leetcode.
I will update my daily learnings here.

Let's start,

DAY 1:
1. MERGE SORT
   Merge Sort is a DEVIDE and CONQUERS algorithm that devides the given array into equal parts and then merges the 2 sorted parts.
   There are 2 main functions:
   1. merge(): This function is responsible for merging 2 halves of the array in a sorted manner assuming that both parts of array are 
               sorted.
   2. mergeSort(): This function devides the array into two parts, such that
      low = leftmost index of the array
      mid = middle index of the array, (low + high) / 2
      high = rightmost index of the array.
  3. We recursively split the array, and go from top to down until subarrays size becomes 1.
