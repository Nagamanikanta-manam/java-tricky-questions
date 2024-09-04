# Java Tricky Questions


## Questions

### Question 1

Consider the following Java code snippet:

```java
public class Main {
    public static void main(String[] args) {
        byte a = "durga";
        System.out.print(a);
    }
}
```
What will be the outcome when you try to compile this program?

A. Compilation Error: incompatible types: String cannot be converted to byte<br>
B. Compilation Error: incompatible types: possible lossy conversion<br>
C. 0<br>
D. Exception<br>
## Answer:<br>
A. Compilation Error: incompatible types: String cannot be converted to byte

## Explanation:<br>
The code will produce a compilation error because a String cannot be assigned to a byte variable.
