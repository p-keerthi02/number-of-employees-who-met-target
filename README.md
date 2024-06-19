class Solution:
    def numberOfEmployeesWhoMetTarget(self, hours: List[int], target: int) -> int:
        x = 0
        for i in hours:
            if i >= target:
                x += 1
        return x
