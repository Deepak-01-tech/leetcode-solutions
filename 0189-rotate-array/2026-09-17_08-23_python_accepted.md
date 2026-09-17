# 189. Rotate Array
  
<br>**Problem:** https://leetcode.com/problems/rotate-array/<br>

**Difficulty:** Medium<br>
**Topics:** Array, Math, Two Pointers<br>
**Language:** python<br>
**Status:** Accepted<br>
**Submitted:** 2026-09-17 08:23 local time

**Runtime:** 35 ms (beats 30.108699999999985%)
**Memory:** 28.1 MB (beats 17.875100000000007%)


<!-- leetgit:submissionId=2144228980 codeHash=6abbd025c784a1d57fc148c2eaa1f661e392389a46de6959d90cd012f2b74af6 notesHash=e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 -->

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
        return nums


        
```
