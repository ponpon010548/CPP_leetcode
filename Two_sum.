class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {
        vector<int> ans;
        for (int j = 0; j < size(nums);j++){
            for(int i = 1 + j; i < size(nums); i++ ){
                int temp = target - nums[j];
                if ((temp - nums[i]) == 0 ){
                    ans.push_back (j);
                    ans.push_back (i);
                    break;
                }
            }
        }
    return ans;
    }
};
