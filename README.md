- š Hi, Iām @veeravel87
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
veeravel87/veeravel87 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->package Week1.day1;

public class Factorial {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int firstnum=0,secondnum=1,range=8,sum;
		System.out.print(firstnum);
		System.out.print(","+secondnum);
		
		for (int i = 1; i <range; i++) {
			
			sum=firstnum+secondnum;
			firstnum=secondnum;
			secondnum=sum;
			System.out.print(","+sum);
		}
			
		}
		

}

