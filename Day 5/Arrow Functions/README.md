## Objective

In this challenge, we practice using arrow functions. Check the attached tutorial for more details.

## Task

Complete the function in the editor. It has one parameter: an array, nums. It must iterate through the array performing one of the following actions on each element:
- If the element is even, multiply the element by 2.
- If the element is odd, multiply the element by 3.
The function must then return the modified array.

**Input 0**
```
5
1 2 3 4 5
```

**Expected Output 0**
```
3 4 9 8 15
```

#### Javascript

```javascript
function modifyArray(nums) {
    const result = nums.map((value)=>{
        if(value%2==0){
            return value*2;
        }
        else{
            return value*3;
        }
    })
    return result;
}
```

