def two_sum(self, nums: List[int], target: int) -> List[int]:
    nums_map = {}
    for i, num in enumerate(nums):
        nums_map[num] = i # value가 index
        
    # 타겟에서 첫 번째 수를 뺀 결과를 키로 조회
    for i, num in enumerate(nums):
        if target - num in nums_map and i != nums_map[target - num]:
            return nums.index(num), nums_map[target - num]
