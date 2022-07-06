W12 Coding Assignment Instructions: Two Functions that Use Arrays
To-Do Date: Jul 6 at 2:59am
Overview
Task: Write two functions that process and manipulate arrays.
Purpose: Write, test, and troubleshoot JavaScript code that uses arrays.
Instructor: Tutors and mentors.
Instructions
In a file named array1.html, write an HTML document that contains a button and a div (text fields are not needed). Copy and paste this code onclick="test()" as the onclick attribute for the button. Then copy and paste this function between the opening and closing script tags in your document.

/* Defining Table
 * Input: no user input
 * Processing: Test the addEnds and getMiddle functions by calling them.
 * Output: The values returned from the addEnds and getMiddle functions.
 */
function test() {
    let list1 = [ 17, 8, 9, 5, 20 ];
    let list2 = [ 12, 4, 8, 15, 17, 5, 20, 11 ];

    // Test the addEnds function by calling it two times.
    let sum1 = addEnds(list1);
    let sum2 = addEnds(list2);

    // Test the getMiddle function by calling it two times.
    let mid1 = getMiddle(list1);
    let mid2 = getMiddle(list2);

    // Build a string to display to the user.
    let output =
            sum1 + '<br>' +
            sum2 + '<br>' +
            mid1 + '<br>' +
            mid2;

    // Display the output string for the user to see.
    document.getElementById('output').innerHTML = output;
}
Also between the two opening and closing script tags, write two functions as follows:

Write a function that returns the sum of the first and last values in an array. The function must have this header:

function addEnds(list)
For example, if the addEnds function were called like this:

var list = [ 17, 8, 9, 5, 20 ];
var value = addEnds(list);
The addEnds function would return 37 because 17 and 20 are the first and last values stored in the array, and the sum of 17 and 20 is 37.

Test Cases
Parameter List	Return
[17, 8, 9, 5, 20]	37
[12, 4, 8, 15, 17, 5, 20, 11]	23
Write a function named getMiddle that returns the value of the middle element in an array. If the array has an even number of elements, then this function must return the average of the two middle elements. The function must have this header:

function getMiddle(list)
For example, if the getMiddle function were called like this:

var list = [ 12, 4, 8, 15, 17, 5, 20, 11 ];
var value = getMiddle(list);
The getMiddle function would return 16 because 15 and 17 are stored in the middle of the array, and the average of 15 and 17 is 16.

Test Cases
Parameter List	Return
[17, 8, 9, 5, 20]	9
[12, 4, 8, 15, 17, 5, 20, 11]	16
Test your functions in Google Chrome.
Submit your file by uploading it into this assignment.