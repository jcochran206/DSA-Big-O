# DSA-Big-O

## Question for Big O
- 1. O(1) one call by individual one action and many can respond
- 1.1 O(n) iterate an array with potential  
- 2. O(1) constant cut down
- 3. O(n^2) inner loop and comparision 
- 4. O(n) doubler use item array and mutiples by each index by 2
- 5. O(n) due to length of parameter provide in search
- 6. O(n^2) based loop iterates on its self
- 7. creates a fib sequence creates an array with the length of the number provided in the argument with a runtime of O(n)
- 8. O(logn) because of it takes sorted array and less the value of n cutting equation by half
- 9. O(1) executes one line of code regardless of number same amount to complete 
- 10. O(n) directly proportional to the size (n) of the input
- 11. O(n) directly proportional to the number of disks algo would be to move next disc to the next stack until disk dot length is reached
- 12. 

function CountSheep(num){
    let i;
    for (i = num; i > 0; i--){
        console.log(`${i} : Another sheep jumps over the fence`)
    }
    return 'All sheep jumped over the fence'
}

console.log(CountSheep(3));



function exponential(a,b){
    var c = 1;
    for(var i=1; i<=b; i++){
        c = c * a;
    }
    return c;
}

console.log(exponential(2,5));
