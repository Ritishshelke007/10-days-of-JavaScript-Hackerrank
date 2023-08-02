## Objective

In this challenge, we practice looping over the characters of string. Check out the attached tutorial for more details.

## Task

1. First, print each vowel in s on a new line. The English vowels are a, e, i, o, and u, and each vowel must be printed in the same order as it appeared in s.
2. Second, print each consonant (i.e., non-vowel) in s on a new line in the same order as it appeared in s.




**Input**
```
javascriptloops
```

**Expected Output**
```
a
a
i
o
o
j
v
s
c
r
p
t
l
p
s
```

#### Javascript

```javascript
function vowelsAndConsonants(s) {
    
    const input = ['a','e','i','o','u'];
    let vowels = [];
    let conso = [];
    
    for (let val of s){
        if(input.includes(val)){
            vowels.push(val);
        }
        else{
            conso.push(val);
        }
    }
    
    vowels.forEach((val) => console.log(val));
    
    conso.forEach((val) => console.log(val));   
}
```

