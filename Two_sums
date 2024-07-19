class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        num_to_index = {}
        for index, y in enumerate(nums):
            x = target - y 
            if x in num_to_index: 
                return [num_to_index[x], index]  
            num_to_index[y] = index  
            

        
