## Objective

Today, we're practicing bitwise operations. Check the attached tutorial for more details.

## Task

We define S to be a sequence of distinct sequential integers from 1 to n; in other words, S = {1,2,3,...n}. 
We want to know the maximum bitwise AND value of any two integers, a and b (where a<b), in sequence S that is also less than a given integer, k.

Complete the function in the editor so that given n and k, it returns the maximum a & b < k.
**Input 0**
```
3
5 2
8 5
2 2
```

**Expected Output 0**
```
1
4
0
```

#### Javascript

```javascript
function getMaxLessThanK(n,k){
    let answer = 0;
    
    for(let i=1; i<n; i++){
        for(let j=i+1 ; j<=n; j++){
            let res = i & j;
            if(res > answer && res < k){
                answer = res;
            }
        }
    }
    return answer;
}
```

