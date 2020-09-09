# Array-popualrise-an-array-


public class Solution {
    
    public static void arrange(int[] arr, int n) {
    	//Your code goes here
        int i=0;
        int j=n-1;
        int c=1;
        while(i<=j)
        {
            if(c%2==1)
            {
                arr[i]=c;
                c++;
                i++;
            }
            else
            {
                arr[j]=c;
                c++;
                j--;
            }
        }
    }
}
