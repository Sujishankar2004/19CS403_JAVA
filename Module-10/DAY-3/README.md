# Ex.No:10(C)             JAVA LIST INTERFACE
 ## AIM :

To Create a List interface implemented by arraylist class , adding n elements to object of List interface and display the list is empty or not.


## ALGORITHM :
1.	Start
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and an empty `ArrayList` named `list`
-	b) Read integer `n`
4.	Check if `list` is empty, print corresponding message
5.	Use a loop to add `n` strings to `list`
6.	Check if `list` is empty again, print corresponding message
7.	End

## PROGRAM:
 ```
/*
Program to implement a JAVA LIST INTERFACE using Java
Developed by: SUJI S
RegisterNumber: 212222040164 
*/
```

## Sourcecode.java:
```
import java.util.*;


public class GFG {

	public static void main(String args[])
	{
		Scanner sc=new Scanner(System.in);
		List<String> al = new ArrayList<>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++)
        {
				al.add(sc.next());
        }

		
		System.out.println(al);
	}
}

```






## OUTPUT:



## RESULT:
Thus the java program implemented a List interface for array list was executed and verified successfully.










