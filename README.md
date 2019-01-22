# quiz-4-7-corrections

### Quiz 4

2. When you are displaying more than one value in the console at once, you must use commas to separate the different values. The commas themselves are not included in the values so the correct answer would be (age 16).

8. For this question, I had selected some falsey values but not all of them simply because I forgot that they were included as falsey values. I also accidentally click -1 as a falsey value as I scrolled down the page. The correct values that are considered falsey are null, undefined, false, NaN, "" and 0.

9. In order to declare a variable, you must use the let keyword and a specific variable( in this case x). After declaring the variable you then assign it a value (in this case 27). 

10. You would need to use the constant declaration because the number pi will not change throughout your code. Since the const Keyword requires the use of the UPPERCASE naming convention, the correct answer, in this case, would be const PI = 3.14.

11. I misplaced a parenthesis causing the second function not to work. 
```

function askedAndAnswered() {

p = document.getElementById("ask-and-asnswered");

let x = prompt("What is your name?");

let y = prompt("How old are you? (enter as number)");

let y = y + 1;

p.innerHtml = alert("Hello, " + x + "." + "When do you turn " + y + "?");
}


function classTrip() {

let y = prompt("How many students are attending the class trip?");

let z = prompt("How many chaperones are attending the class trip?");

let max = prompt("What is the maximum capcity of a single bus? (not including the bus driver)");

let num = y + z

let x = num / max

console.log(x + "busses are required to accommodate" + y + "students and" + z + "chaperones.");
}

```

### Quiz 5

2. When I answered this question, I included = as an answer due to pure stress and the sheer amount of options available in this question. The correct list of relational operators is  !==, !=, ==, ===, <=, >=, < and >.

4. For this question, I answer that the logical operators were !, ||, and &&. This answer was wrong because I forgot the logical operators of ? and !==.

6. When I first completed this question I chose the correct answer however as I was swiping down to switch questions I accidentally clicked the mouse again and chose another wrong answer. The correct answer works because it uses the and If statement in order to test the many cases of the student's possible grade and assign it a numerical value in the simplest way possible. 

8. For this question, my answers misplaced the semicolons in each code section. I placed the semicolons before writing what goes inside of each statement, making my answers wrong and the answers in which the semicolons are placed after the statement are correct. 

9. For this question, I only chose two of the three working tertiary operators. The operator that I forgot to chose is correct because the change of signs causes this statement to work for the desire of the function. 


11. For this question, my answer is incorrect because I thought that I needed to loop the entire function from the beginning. This is incorrect because the first step, the setup, does not need to be repeated after it is completed the first time the function runs.

12. This question was answered incorrectly because i accidentally clicked the wrong one when swiping to change the question. The for, while, and do while loops can each be used to achieve the same result. 

13. For this question, the answer that I selected that was incorrect is wrong because it does not follow the format need to use a do while loop. The correct answer that I missed uses the do while loop correctly and achieves the wanted results. 

14. This question was originally answered incorrectly as I assumed the while and do while loops differed in the number of times the check their conditions. 

15. This question is incorrect because the option of code I chose does not actually declare i as a variable like the correct one does cause my answer to be incorrect. Since my answer failed to declare i as a function, the overall function will fail. 

### Quiz 6

1. For this problem, I forgot to select two other correct options of code. The first option takes the product of x, y, and z, assigns it to the variable product, and returns the variable product. The second option uses if statements to account for all options if and values are left undefined but still ultimately satisfies the problem's requirements. Since these two options were correct and I did not choose them, the answer was incorrect.

2. In order to address an array, you must fill in all values or else it will display undefined. Since there is no value to fill in for variable C, then when C is called upon it will display as undefined. 

4. This question I incorrect because it is unnecessary to prompt the user for a value for a and b. Since these value would be filled when the function is called upon there is no need to prompt the user making my answer incorrect and the second option correct. 

7. For this question, I chose the wrong function because I thought I would be best to use variables that were clear about what values would be entered into them. This is incorrect as shown that the correct answer uses x and y to represent the base and the power at which it is being raised. 

9. This question was answered incorrectly due to me accidentally selecting the incorrect answer when scrolling to proceed to the next question. The correct built-in function that returns a value is the prompt function. 

10. This question was answered incorrectly due to me accidentally selecting the incorrect answer when scrolling to proceed to the next question. I had already selected the correct answers and the one selected by accident was clearly incorrect as it does not follow the correct format for this function to execute correctly.

11. This question was answered incorrectly because undefine will not be inside of the console. Since d is defined as 4 and d is the only thing that was being printed to the console, 4 is the only value to appear in the console. 

13. This was incorrect because I said that 1 and 2 would be printed to the console and this was incorrect. Since the console.log function is outside the if statement and the variable were declared with var keyword a reference error will occur at line 10. 

### Quiz 7
1. I got this question incorrect for failing to include the second option in my answer. Since the second option also achieves the desired goal of accepting an array of elements and printing each one to the screen one-by-one, it can be accepted as a correct answer. 

2. I got this question wrong because I selected the third option instead of the second option. The questions requirements can be met by using ``cars.lastIndexOf(car) !== -1`` as it is in the second option so it can be considered correct. 

4. This question was answered incorrectly as I chose the third option instead of the second option. The code snippet will include 0 but exclude 20 which is why the second option is correct. 

11. I answered this question incorrectly because i thought since 4444 was included in the array and it didn't satisfy the return parameters, the answer had to be false. This is incorrect as even though the array includes 4444 the answer is true.

14. For this question, I chose the incorrect answer of the first option. The fourth option is actually correct because getLargest in this case will return all negative numbers, which is not the goal of the function.
