## Objective

In this challenge, we practice using JavaScript classes. Check the attached tutorial for more details.

## Task

Create a Polygon class that has the following properties:
- A constructor that takes an array of integer values describing the lengths of the polygon's sides.
- A perimeter() method that returns the polygon's perimeter.
Locked code in the editor tests the Polygon constructor and the perimeter method.

**Output Format**
The perimeter method must return the polygon's perimeter using the side length array passed to the constructor.

#### Javascript

```javascript
function getCount(objects) {
class Polygon{
    constructor(arr){
        this.arr = arr;
    }
    perimeter(){  
    const result = this.arr.reduce((acc,cur)=>{
       return acc+=cur; 
    },0);  
    return result;
    }
}
```

