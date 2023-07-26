# ArrayList Printing
## Quetion
* Declare an ArrayList as arr.
* Take  as an integer input.
* Take  elements inside the ArrayList.
* Print the ArrayList from the starting using for loop and for-each loop.

## Sample Input 
java
5
1 2 3 4 5


## Sample Output
java
1 2 3 4 5 
1 2 3 4 5 


## Explanation
* *Arr=[1,2,3,4,5]*

## *Answer Code*
```java
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        List<Integer> arr=new ArrayList<>();
        for(int i=0; i<n; i++)
            arr.add(sc.nextInt());
                    for(int i=0; i<n; i++)
                    System.out.print(arr.get(i)+ " ");
                    System.out.println();
                    for(int ele: arr)
                    System.out.print(ele+ " ");
    }
}
