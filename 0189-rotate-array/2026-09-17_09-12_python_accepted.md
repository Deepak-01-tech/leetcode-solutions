# 189. Rotate Array
  
<br>**Problem:** https://leetcode.com/problems/rotate-array/<br>

**Difficulty:** Medium<br>
**Topics:** Array, Math, Two Pointers<br>
**Language:** python<br>
**Status:** Accepted<br>
**Submitted:** 2026-09-17 09:12 local time

**Runtime:** 7 ms (beats 74.36019999999999%)
**Memory:** 26.7 MB (beats 49.050000000000004%)


<!-- leetgit:submissionId=2144257200 codeHash=e5db236b46236773d85b575be046747b8bd657eef082e04646b8f31cb0c6a3d2 notesHash=e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 -->

## Solution

```python
class Solution(object):
    def rotate(self, nums, k):
        """
        :type nums: List[int]
        :type k: int
        :rtype: None Do not return anything, modify nums in-place instead.
        """
        k%=len(nums)
        nums[:]=nums[-k:]+nums[:-k]


        
```
