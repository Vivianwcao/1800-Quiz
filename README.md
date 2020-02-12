Q1: Is the keyword "fixes" the only way to auto-close an issue from a PR 
(pull request). Is there other keywords that can accomplish the same thing?

You may also the following:
close
closes
closed
fix
fixed
resolve
resolves
resolved

Q2: Do you have to create a new PR EVERYTIME you want to close an issue,
or is it possible to close multiple issues within a single PR? If so, 
how?
Yes you may. you may use key words to close more than 1 issue.
For example: Close #1 #2 #3.
Anyone with write permissions to a repository can manually link a pull request to an issue.
You can manually link up to ten issues to each pull request.
The issue and pull request must be in the same repository.

Q3: Provide an example of using map that is different from the one I have done.
Your example must use map both as a named function declaration and with an
anonymous function. 

<script>
let myList = [1, 3, 5, 8, 9];
let newList = myList.map(calculation)
function calculation(number){
    if (number < 4){
        return number + 
        2; 
    } 
    else
    {
        return number - 2;
    }
} 

console.log(newList)
</script>

Within comments, explain exactly what map is doing. Finally, why is the
"transformation function" we discussed in class sometimes referred to 
as a callback function. 

The map() method creates a new array with the results of calling a function for every array element.
A basic map() looks like this: array.map(function) where every element in the array will be passed to the function called, 
and the returned elemenst will be store in a new array in the same order.
A callback function is passed into another function as an argument, 
which is then invoked inside the outer function to complete a task. In the example of map(), 
the callback function transforms each element of the original array. The inner function transformations and is being called back by map().

