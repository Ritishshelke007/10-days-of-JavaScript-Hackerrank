## Objective

In this challenge, we use a Regular Expression to evaluate a string. Check out the attached tutorial for more details.

## Task

Complete the function in the editor below by returning a RegExp object, re, that matches any string s that begins and
ends with the same vowel. Recall that the English vowels are a, e, i, o, and u.

**Input 0**
```
bcd
```

**Expected Output 0**
```
false
```
**Input 1**
```
abcda
```

**Expected Output 1**
```
true
```

#### Javascript

```javascript
function regexVar() {
    const re = /^([aeiou]).+\1$/
    // ^ $ - start and end with ([aeiou]) - any of group .+ one or more char in between 
    return re;
}
```

