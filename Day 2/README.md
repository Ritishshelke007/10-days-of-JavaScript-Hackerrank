## Objective

Today, we're discussing JavaScript functions. Check out the attached tutorial for more details.

## Task

Implement a function named factorial that has one parameter: an integer, n. It must return the value of n!(i.e.,  factorial).

**Input**
```
4
```

**Expected Output**
```
24
```

#### Javascript

```javascript
function factorial(n){ 
    let fact=1;    
    if(n==0 || n==1){
        return fact;
    }  
    for(let i=1; i<=n; i++){
        fact=fact*i;
    } 
    return fact;
}

function main() {
    const n = +(readLine());
    
    console.log(factorial(n));
}
```

