//Didn't get this in my whiteboarding session on Friday, didn't get to question five before 3:00pm. Took an idea I had while whiteboarding (using Math.min) to pull the smallest value of an array and push it into a new one and figured out how to do that on Saturday. Lot's of "let" used. But the original array isn't altered and it returns the same thing every time. So kind of functional??? 


const sort = (array) => {
    let toSort = [...array];
    let sorted = [];
    for(i=0;i=toSort.length;i++){
    let x = Math.min(...toSort);
    toSort.splice(toSort.indexOf(x),1);
    sorted.push(x);
    }
    return sorted;
    }

   