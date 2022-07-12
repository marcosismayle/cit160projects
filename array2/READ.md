In a file named array2.html, write an HTML document that contains a button and a div (text fields are not needed). Copy and paste this code onclick="test()" as the onclick attribute for the button. Then copy and paste this function between the opening and closing script tags in your document.

/* Defining Table
 * Input: no user input
 * Processing: Test the countEvens and multiply functions by calling them.
 * Output: The values returned from the countEvens and multiply functions.
 */
function test() {
    let list1 = [ 17, 8, 9, 5, 20 ];
    let list2 = [ 12, 4, 8, 15, 17, 5, 20, 11 ];

    // Test the countEvens function by calling it two times.
    let count1 = countEvens(list1);
    let count2 = countEvens(list2);

    // Test the multiply function by calling it two times.
    let mult1 = multiply(list1,3);
    let mult2 = multiply(list2,2);

    // Build a string to display to the user.
    let output =
            count1 + '<br>' +
            count2 + '<br>' +
            mult1 + '<br>' +
            mult2;

    // Display the output string for the user to see.
    document.getElementById('output').innerHTML = output;
}
Also between the two opening and closing script tags, write two functions as follows:

Write a function named countEvens that counts and returns the number of even integers in an array. The function must have this header:

function countEvens(list)
For example, if the countEvens function were called like this:

var list = [ 17, 8, 9, 5, 20 ];
var count = countEvens(list);
The countEvens function would return 2 because 8 and 20 are even integers.

Test Cases
Parameter List	Return
[17, 8, 9, 5, 20]	2
[12, 4, 8, 15, 17, 5, 20, 11]	4
Write a function to multiply each element in an array by some value and to return the products in an array. The function must have this header:

function multiply(list, multiplier)
For example, if the multiply function were called like this:

var list = [ 17, 8, 9, 5, 20 ];
var products = multiply(list, 3);
The multiply function would return an array with these values: [ 51, 24, 27, 15, 60 ].

Test Cases
Parameter List	Multiplier	Return
[17, 8, 9, 5, 20]	3	[ 51, 24, 27, 15, 60 ]
[12, 4, 8, 15, 17, 5, 20, 11]	2	[24, 8, 16, 30, 34, 10, 40, 22]