## Objective

In this challenge, we learn about JavaScript Dates. Check out the attached tutorial for more details.

## Task

Given a date string, dateString, in the format MM/DD/YYYY, find and return the day name for that date. Each day name must be
one of the following strings: Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, or Saturday. For example, the day name for the date 12/07/2016 is Wednesday.

**Input 0**
```
2
10/11/2009
11/10/2010
```

**Expected Output 0**
```
Sunday
Wednesday
```

#### Javascript

```javascript
function getDayName(dateString) {
    const days = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
    let dayName;
    const d = new Date(dateString);

    dayName = days[d.getDay()];
    return dayName;
}
```

