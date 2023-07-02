class Solution {
    public void moveZeroes(int[] nums) {
        for (int i = 0, j = 1; j < nums.length; j++) {
            if (nums[i] == 0 && nums[j] != 0) {
                int tmp = nums[i];
                nums[i] = nums[j];
                nums[j] = tmp;
            }

            if (nums[i] != 0) {
                i++;
            }
        }
    }
}
