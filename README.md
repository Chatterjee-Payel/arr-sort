# arr-sort
class Solution {
  public:
    bool arraySortedOrNot(int arr[], int n) {
        // code here
        int count=0;
        for(int i=0;i<n-1;i++){
            if(arr[i]<arr[i+1])
            count++;
            if(arr[i]==arr[i+1])
            count++;
            
        }
        if(count==n-1)
        return true;
        else
        return false;
    }
    
};
