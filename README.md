- 👋 Hi, I’m @crazy159-ai
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
crazy159-ai/crazy159-ai is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
leetcode:https://leetcode-cn.com/problems/two-sum
class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {
        int n=nums.size();
        for(int i = 0;i<n;i++){
            for(int j =i+1;j<n;j++)
            {
                if(nums[i] + nums[j]== target)
                return {i,j};
            }
        }
        return {};

    }
};
