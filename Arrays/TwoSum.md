# Two Sum
🔗 [Problem Link] https://leetcode.com/problems/two-sum/description/
### ✅ Code (JavaScript)

const nums = [2, 7, 11, 15];
let target = 18;
var twoSum = function (nums, target) {
    for (i = 0; i < nums.length; i++) {
        for (j = i+1; j < nums.length; j++) {
            if (nums[i] + nums[j] == target) {
                return [i,j]
            }

        }

    }
};
let result = twoSum(nums, target);
console.log(result);
