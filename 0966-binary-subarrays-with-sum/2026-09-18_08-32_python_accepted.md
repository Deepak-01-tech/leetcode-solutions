# 966. Binary Subarrays With Sum
  
<br>**Problem:** https://leetcode.com/problems/binary-subarrays-with-sum/<br>

**Difficulty:** Medium<br>
**Topics:** Array, Hash Table, Sliding Window, Prefix Sum<br>
**Language:** python<br>
**Status:** Accepted<br>
**Submitted:** 2026-09-18 08:32 local time

**Runtime:** 47 ms (beats 20.137499999999957%)
**Memory:** 14.9 MB (beats 41.53339999999996%)


<!-- leetgit:submissionId=2145285783 codeHash=eb344528a7dd770dad945c0f848aff58fc3ee24b196d97863f9d38ac6c45021b notesHash=e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 -->

## Solution

```python
class Solution(object):
    def numSubarraysWithSum(self, nums, goal):
        hashmap={0:1}
        l=0
        r=0
        sum1=0
        count=0
        while r<len(nums):
            sum1+=nums[r]
            if sum1-goal in hashmap:
                count+=hashmap[sum1-goal]
            hashmap[sum1]=hashmap.get(sum1,0)+1
            r+=1
        return count
        
```
