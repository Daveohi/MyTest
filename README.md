# MyTest
Level of contribution 

Given an array of integers nums and an integer target, create a function that returns the two

numbers such that they add up to target.

You may assume that each input would have exactly one solution, and you may not use the
same element twice.
Example:
Input: nums = [2,7,11,15], target = 9
Output: [2,7]
Explanation: Because 2 + 7 == 9, we return [2, 7]
Constraints:
You can return the answer in any order
Only one valid answer exists


def twoSum(self, nums: List[int], target: int) -> List[int]:
    for i in range(len(nums)):
        for j in range(i+1, len(nums)):
            s=num[i]+nums[j]
            if s==target:
                return [i, j]
