## Objective

In this challenge, we learn about strings and exceptions. Check out the attached tutorials for more details.

## Function Description 

Complete the reverseString function; it has one parameter, s. You must perform the following actions:

1. Try to reverse string  using the split, reverse, and join methods.
2. If an exception is thrown, catch it and print the contents of the exception's message on a new line.
3. Print  on a new line. If no exception was thrown, then this should be the reversed string;
   if an exception was thrown, this should be the original string.

**Input 0**
```
"1234"
```
**Expected Output 0**
```
4321
```
**Input 1**
```
Number(1234)
```
**Expected Output 1**
```
s.split is not a function
1234
```

#### Javascript

```javascript
function reverseString(s) {
    try{
    const revString = s.split("").reverse().join("");
    console.log(revString)
    }
    catch(e){
        console.log('s.split is not a function');
        console.log(s);
    }
}
```

