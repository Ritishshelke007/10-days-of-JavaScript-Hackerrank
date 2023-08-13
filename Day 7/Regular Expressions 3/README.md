## Task
Complete the function in the editor below by returning a RegExp object, re, that matches every integer in some string s.

**Input 0**
```
102, 1948948 and 1.3 and 4.5
```

**Expected Output 0**
```
102
1948948
1
3
4
5
```
#### Javascript

```javascript
function regexVar() {
    /*
     * Declare a RegExp object variable named 're'
     * It must match ALL occurrences of numbers in a string.
     */
    const re = /\d+/g

    return re;
}
```

