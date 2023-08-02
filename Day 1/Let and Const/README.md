## Objective

In this challenge, we practice declaring variables using the let and const keywords. Check out the attached tutorial for more details.
## Task

1. Declare a constant variable, PI , and assign it the value Math.PI. You will not pass this challenge unless the variable is declared as a constant and named PI (uppercase).
2. Read a number, r, denoting the radius of a circle from stdin.
3. Use PI and r to calculate the **area** and **perimeter** of a circle having radius r.
4. Print area as the first line of output and print perimeter as the second line of output.

**Input**
```
2.6
```

**Expected Output**
```
21.237166338267002
16.336281798666924
```

#### Javascript

```javascript
function main() {
    const r = readLine();
    const PI = Math.PI;
    
    const area = PI*r*r;
    const perimeter = 2*PI*r;
    
    console.log(area);
    console.log(perimeter);
    }
```

