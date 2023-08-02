## Objective

In this challenge, we learn about Arrays. Check out the attached tutorial for more details.

## Function Description 

Complete the getSecondLargest function in the editor below.

getSecondLargest has the following parameters:

- int nums[n]: an array of integers

**Input**
```
5
2 3 6 6 5
```

**Expected Output**
```
5
```

#### Javascript

```javascript
function getSecondLargest(nums) {
    const mySet = new Set(nums);
  
    const arr2 = Array.from(mySet);
    
    arr2.sort((a,b)=>b-a);
    
    return arr2[1];
}
```

