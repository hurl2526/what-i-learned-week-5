 
# **What I Learned Week 5**
## **Day 19** 

# Using the Debugger : 
* click on left side to make a break point 
* make sure the function is called
* cmnd shift p start debugging or fn/ f5 select node
* Can go line by line to see how function is operating in what order


ESlint installed to help with syntex errors.  
 can write your own rules to let you know when there is an error.   
 can also cmnd shift p correct all errors to correct all like semicolons

## **Day 20**
went over string theory in the morning

# Arrays:

`const classroom = ['patrick', 'steven', 'hurley']
console.log(classroom);
console.log(classroom[2]);
const grades = [90,15,65,87,90];
console.log(grades[4]);
for (let i =0; i <classroom.length; i++){
  console.log(classroom[i]);
}

const firstLetter = classroom[0][0];
console.log(firstLetter);

const student = 'collin';
console.log(student.toLocaleUpperCase());

classroom[0] = classroom[1];
console.log(classroom);

classroom[classroom.length] = 'is great';
console.log(classroom);
// harder way to add to the end

classroom.push('the best');
console.log(classroom);
// easy way to add to the end
classroom.unshift('mike')
console.log(classroom)
// adds to beggining 
classroom.pop();
console.log(classroom)
// got rid of last thing
classroom.shift();
console.log(classroom)
// got rid of first thing

const fiveK = [];
// this is an empty array

fiveK.push(classroom[3]);
console.log(fiveK)
// this is grabbing values from somehting and adding them to new array at the end and keep adding

console.log(fiveK.includes('patrick'));
// looking in our new array to see if it includes something`

## **Day 21**  
Went over assignment 

further into arrays  


Pop  - gets rid of last item

shift  - gets rid of first thing

reverse  - reverses order of string

Splice - delete things in the middle, startng at what index, delet how many things  

Slice used if you want to grab things but not change the original array.   

 starting at what index, ending one before the index you input, 2,6 would give index 2-5

.join makes a string out of array  

Split takes a string and makes an array

concat combines arrays without changing original
newVariable =  array1.concat(array2)


**keyboard shortcuts to remember**  
* multiplt cusors: click at end of one word 
* option click at end of another word.
* Also, highlight a word and then click command D to grab the next of same word  
* select word, command shift L selects them all