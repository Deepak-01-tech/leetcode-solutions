# 595. Big Countries
  
<br>**Problem:** https://leetcode.com/problems/big-countries/<br>

**Difficulty:** Easy<br>
**Topics:** Database<br>
**Language:** mysql<br>
**Status:** Accepted<br>
**Submitted:** 2026-09-29 19:00 local time

**Runtime:** 289 ms (beats 85.86580000000004%)
**Memory:** 0 MB (beats 100%)


<!-- leetgit:submissionId=2157119361 codeHash=562e9d8682a7066cb7f3fceb0d300bacf9f9a62f1e684aa2ad72cd00a9b2eca6 notesHash=e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 -->

## Solution

```mysql
# Write your MySQL query statement below
select name,population,area from World where population>=25000000 or area>=3000000 ;
```
