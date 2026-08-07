# HackerRank Challenge #1: Java If-Else

## Problem Statement
Given an integer $N$, perform conditional actions based on whether it is odd or even and its range:
- If $N$ is odd, print "Weird".
- If $N$ is even and in the range 2 to 5, print "Not Weird".
- If $N$ is even and in the range 6 to 20, print "Weird".
- If $N$ is even and greater than 20, print "Not Weird".



## FINAL ANSWER
<img width="656" height="506" alt="image" src="https://github.com/user-attachments/assets/0e14f72c-c071-4da2-bb7e-ea6f59febe3d" />


🌐 [View RAW Java file](./code.java)

## Explanation
I initially thought of grouping the logic into a single `if-else` block (`N % 2 != 0 || (N >= 6 && N <= 20)`) to simplify the conditions, which passes all test cases successfully. However, I decided to stick directly to the problem's explicit requirements by using separate `if / else if` conditions for each range. This keeps the code literal, readable, and directly aligned with the problem statement while yielding the exact same output. 

But if you're curious about what I was originally thinking, here is a quick example:
```Java
import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.regex.*;

public class Solution {

    private static final Scanner scanner = new Scanner(System.in);

    public static void main(String[] args) {
      int N = scanner.nextInt();
      scanner.skip("(\r\n|[\n\r\u2028\u2029\u0085])?");        
      
      if (N % 2 != 0 || (N >= 6 && N <= 20)){
            System.out.println("Weird");
        } else {
            System.out.println("Not Weird");
        }
        
        scanner.close();
    }
}
```

## Screenshot

<img width="716" height="656" alt="image" src="https://github.com/user-attachments/assets/11c07094-2b5a-42db-ac46-38ad26370430" />

🌐 [View Screenshot file](./screen.java)
