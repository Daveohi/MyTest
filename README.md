# MyTest
Level of contribution 

def twoSum(self, nums: List[int], target: int) -> List[int]:
    for i in range(len(nums)):
        for j in range(i+1, len(nums)):
            s=num[i]+nums[j]
            if s==target:
                return [i, j]
