# Pyramid-Pattern
A simple java program on pyramid pattern.<br/>To make the program simple we did not use any Scanner class for input.<br/>For loop is being used mainly.
```java
for(i=1;i<=n;i++)
		{
		for(j=1;j<=l;j++)
		{
		System.out.print(" ");
		}
		  for(k=1;k<=2*i-1;k++)
    		{
	    	System.out.print("*");
		    }
  		l--;
	  }
```
in the last for loop we have used the formula 
```java
		for(k=1;k<=2*i-1;k++)
 ```
since we need a pyramid pattern of
```
     *
    ***
   *****
  *******
 *********
 ```
which is of the order 2*i-1.
