## Objective

In this challenge, we practice using throw and catch statements to work with custom error messages.

## Task

Complete the isPositive function below. It has one integer parameter, a. If the value of a is positive,
it must return the string YES. Otherwise, it must throw an Error according to the following rules:
- If a is 0, throw an Error with message = Zero Error
- If a is negative, throw an Error with message = Negative Error

**Input 0**
```
3
1
2
3
```

**Expected Output 0**
```
YES
YES
YES
```
**Input 1**
```
3
2
0
6
```

**Expected Output 1**
```
YES
Zero Error
YES
```

#### Javascript

```javascript
function isPositive(a) {
    try{
        if(a>0){
            return "YES";
        }
        else if(a===0){
            throw "Zero Error";
        }
        else if(a<0){
            throw "Negative Error";
        }
    }
    catch(e){
        return e;
    }
}
```

