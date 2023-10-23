class Solution {
    public List<Integer> getRow(int rowIndex) {
       List<Integer> dp = new ArrayList<>();
       dp.add(1);
       for(int i = 1 ; i <= rowIndex ; i++){
           List<Integer> temp = new ArrayList<>();
           temp.add(1);
           for(int j = 1; j < i ; j++){
               int sum = dp.get(j-1) + dp.get(j);
               temp.add(sum);
            }
            temp.add(1);
            dp = temp;
        }
       return dp;
    }
}
