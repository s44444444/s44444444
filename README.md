- 👋 Hi, I’m @s44444444
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
s44444444/s44444444 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

java
public class Main
{
	public static void main(String[] args) {
// 		System.out.println("Hello World");
	
	    double[] nums = {11.2,23.5,63.6};
	    int i;
	    // listing all array;
	    for (i = 0; i < nums.length; i++) {
	        System.out.println( "(" + i + ") " +nums[i]);
	    }
	    double total = 0;
	    // sum of array;
	    for (i = 0; i < nums.length; i++) {
	        total += nums[i];
	    }
	    System.out.println( "sum : " + total);
	    // finding the max number in array;
	    double max = 0;
	    for (i = 0; i < nums.length; i++) {
	        if(nums[i] > max) max = nums[i];
	    
	    }
	    System.out.println("maaximun : " + max);
	    // finding the minimun number in array;
	    double min = max;
	    for (i = 0; i < nums.length; i++) {
	        if(nums[i] < min) min = nums[i]; 
	    }
	    System.out.println("minimum : " + min);
	    
	    //using forEach loop;
	    for(double elements : nums) {
	        System.out.println(elements);
	    }
	    }
}
