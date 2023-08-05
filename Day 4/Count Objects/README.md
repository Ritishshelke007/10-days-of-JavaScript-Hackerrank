## Objective

In this challenge, we learn about iterating over objects. Check the attached tutorial for more details.

## Task

Complete the function in the editor. It has one parameter: an array, a, of objects. Each object in the array
has two integer properties denoted by x and y. The function must return a count of all such objects o in array a that satisfy o.x==o.y

**Input 0**
```
5
1 1
2 3
3 3
3 4
4 5
```

**Expected Output 0**
```
2
```
#### Javascript

```javascript
function getCount(objects) {
    let count = 0;
    
    objects.forEach((object)=>{
        if(object.x===object.y){
            count+=1;
        }
    })
    return count;
}
```

