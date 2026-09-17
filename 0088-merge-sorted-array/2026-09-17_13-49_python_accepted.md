# 88. Merge Sorted Array
  
<br>**Problem:** https://leetcode.com/problems/merge-sorted-array/<br>

**Difficulty:** Easy<br>
**Topics:** Array, Two Pointers, Sorting<br>
**Language:** python<br>
**Status:** Accepted<br>
**Submitted:** 2026-09-17 13:49 local time

**Runtime:** 0 ms (beats 100%)
**Memory:** 12.4 MB (beats 21.840400000000017%)


<!-- leetgit:submissionId=2144498290 codeHash=5c18f4f5c6e3ae70358d6647cb8ba487bb45413db3854e6269c05f42c5632e16 notesHash=e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 -->

## Solution

```python
class Solution(object):
    def merge(self, nums1, m, nums2, n):
        """
        :type nums1: List[int]
        :type m: int
        :type nums2: List[int]
        :type n: int
        :rtype: None Do not return anything, modify nums1 in-place instead.
        """
        nums1[:]=nums1[:m]
        nums1[:]=sorted(nums1+nums2)
        
```
