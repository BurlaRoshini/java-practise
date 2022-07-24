# java-practise
John and Johnny are playing a square-square game. John gives a task to Johnny. If Johnny completes the task in a given time, she will win the game.

Johnny has an array of numbers sorted in non-decreasing order. She has to do the squares of numbers of the array and return the array in non-decreasing order.

Help Johnny so that she can win the game.



import java.util.Arrays;
import java.util.Scanner;
public class Solution 
{
	public static void main(String[] args) {
	    int n;
	    Scanner sc=new Scanner(System.in);
	    n=sc.nextInt();
	    int[] arr = new int[n];
	    for(int i=0;i<n;i++)
	    {
	        arr[i]=sc.nextInt();
	    }
	    Arrays.sort(arr);
		//System.out.println(Arrays.toString(arr));
		int square = 0;
		for(int i=0;i<n;i++){
		     square = arr[i]*arr[i];
	
		System.out.print(square + " ");
		}
		
	}
}
