# 162. Find Peak Element
  
<br>**Problem:** https://leetcode.com/problems/find-peak-element/<br>

**Difficulty:** Medium<br>
**Topics:** Array, Binary Search<br>
**Language:** python<br>
**Status:** Accepted<br>
**Submitted:** 2026-09-28 11:08 local time

**Runtime:** 0 ms (beats 100%)
**Memory:** 12.4 MB (beats 89.8879%)


<!-- leetgit:submissionId=2155609291 codeHash=2522b0d7c47e1e7daca46927a84c71a2a08db19f798c2fd527302ceb9fd2a8fa notesHash=e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 -->

## Solution

```python
class Solution(object):
    def findPeakElement(self, nums):
        """
        :type nums: List[int]
        :rtype: int
        """
        maxi=max(nums)
        return nums.index(maxi)
        
        
```
