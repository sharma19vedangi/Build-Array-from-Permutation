# Build-Array-from-Permutation
#Array-Leetcode Problem Solution
class Solution {
    public int[] buildArray(int[] nums) {
        int ans[]=new int[nums.length];
        int temp;
        for(int i=0;i<nums.length;i++)
        {
             temp=nums[i];
            ans[i]=nums[temp];
        }
        return ans;
    }
}
