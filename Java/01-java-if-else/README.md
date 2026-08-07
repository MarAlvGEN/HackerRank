# HackerRank Challenge #1: Java If-Else

| Domain | Key Concepts | Difficulty | Recommended Docs |
| :---: | :---: | :---: | :---: |
| [Java README](../README.md) | Control Flow, Conditionals | Easy | [Oracle Java Docs](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/if.html) |
---

## Problem Statement

Given an integer $N$, perform conditional actions based on whether it is odd or even and its range:

- If $N$ is odd, print **"Weird"**.
- If $N$ is even and in the range 2 to 5, print **"Not Weird"**.
- If $N$ is even and in the range 6 to 20, print **"Weird"**.
- If $N$ is even and greater than 20, print **"Not Weird"**.

---

## Final Answer

<img width="656" alt="Final Code Execution" src="https://github.com/user-attachments/assets/0e14f72c-c071-4da2-bb7e-ea6f59febe3d" />

> IDE Screenshot: Check the code down below.

🌐 [View RAW Java file](./code.java)

---

## Solution Explanation & Approach

I initially thought of grouping the logic into a single `if-else` block (`N % 2 != 0 || (N >= 6 && N <= 20)`) to simplify the conditions, which passes all test cases successfully. However, I decided to stick directly to the problem's explicit requirements by using separate `if / else if` conditions for each range. This keeps the code literal, readable, and directly aligned with the problem statement while yielding the exact same output.

If you're curious about what I was originally thinking, here is a quick example:

```java
if (N % 2 != 0 || (N >= 6 && N <= 20)) {
    System.out.println("Weird");
} else {
    System.out.println("Not Weird");
}
```

 ## Screenshot


<img width="716" height="656" alt="image" src="https://github.com/user-attachments/assets/11c07094-2b5a-42db-ac46-38ad26370430" />


🌐 [View Screenshot file](./screen.java) 

---

<div align="center">

| [⬅️ Challenge #00](../00-welcome-to-java/README.md) | [Challenge #02 ➡️](../02-java-stdin-and-stdout-i/README.md) |
| :---: | :---: |

</div>
