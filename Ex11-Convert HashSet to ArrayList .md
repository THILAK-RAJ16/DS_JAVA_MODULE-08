# Ex11 Convert HashSet to ArrayList in Java
## DATE:
## AIM:
To convert a collection of distinct integers stored in a HashSet into an ArrayList and display its contents.
## Algorithm
```text
1. Start
2. Read the integer n (number of elements)
3. Create an empty HashSet of integers called set
4. Repeat n times:
   a) Read an integer x
   b) Insert x into set
5. Create an ArrayList of integers called list and initialize it with set
6. Traverse list and display each element
7. End
```
## Program:
Program to To convert a collection of distinct integers stored in a HashSet into an ArrayList and display its contents.
```java
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        HashSet<Integer> set = new HashSet<>();
        for (int i = 0; i < n; i++)
            set.add(sc.nextInt());
        ArrayList<Integer> list = new ArrayList<>(set);
        for (int x : list)
            System.out.print(x + " ");
        sc.close();
    }
}

```
Developed by: THILAK RAJ . P
RegisterNumber:  212224040353


## Output:



## Result:
The program successfully converts a collection of distinct integers stored in a HashSet into an ArrayList
