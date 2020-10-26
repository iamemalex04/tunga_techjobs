# Functions
## Part 1

```javascript
// difference
function difference (num1,num2){
    return num1 - num2
}

// product
function product (num1,num2){
    return num1 + num2
}

// printDay
function printDay
(day){
    let weekDays = {
        1: "Monday", 
        2: "Tuesday", 
        3: "Wednessday", 
        4: "Thursday", 
        5: "Friday",
        6: "Saturday",
        7: "Sunday" }
   
        return weekDays[day]

}

// lastElement
function lastElement (arr){
    let lastElementInArray = arr.pop();
    return lastElementInArray;
}

// numberCompare
function numberCompare(num1, num2){
    
    if (num1 === num2){
    return "Numbers are equal";
    } else if (num1 > num2){
    return "First is greater";
    }
    return "Second  is greater";

}

//singleLetterCount
function singleLetterCount(str, letter){
    let letterCount = 0;
    for(let i=0; i< str.length; i++){
        if(str[i].toLowerCase() === letter.toLowerCase()){
            letterCount++;
        }
    }
    return letterCount;
}

```