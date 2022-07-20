Write a simple JavaScript function named makeFullName with two parameters named givenName and familyName. The function should return a string that contains the family name, a comma, and the given name. For example, if the function were called like this:

var fn = makeFullName("Theodore", "Roosevelt");
it would return "Roosevelt, Theodore" without the double quotes.

Test Cases
Parameters	Return
givenName	familyName
"Theodore"	"Roosevelt"	"Roosevelt, Theodore"
"Barak"	"Obama"	"Obama, Barak"
"Donald"	"Trump"	"Trump, Donald"

--------------------------------------------------------------------------

Write a JavaScript function named depreciation that has three parameters named startValue, endValue, and months. This function should compute and return the monthly depreciation value of an asset given by this formula:

d =  (s - e)
m
where d is the monthly depreciation value, s is the starting value of an asset, e is the ending value, and m is the number of months someone will own the asset.

Test Cases
Parameters	Return
startValue	endValue	months
1000.95	950.47	8	6.31
28000	26200	12	150

--------------------------------------------------------------------

Write a JavaScript function named getLast that takes one parameter: an array named list and returns the value of the last element in list.

Test Cases
Parameter	Return
list
[ -3, 0, 7.1, 5 ]	5
[ 17, 8, 9, 5, 20 ]	20
[ 5, -2.1, 6.3, 9, 5, 13 ]	13

--------------------------------------------------------------------

Write a JavaScript function named averageBig with this header

function averageBig(list) {
The parameter list is an array that contains numbers. The length of the list array will vary. Your function must compute the average of all the numbers stored in the array that are larger than 1000. For example, if your function were called like this:

var list = [70, 1010, 950, 2014, 6];
var score = averageBig(list);
your function would return the number 1512. If none of the numbers in the array are larger than 1000, your function must return 0 (zero).

Test Cases
Parameter	Return
list
[ 70, 1010, 950, 2014, 6 ]	1512
[ -72.3, 3000, 873, 2312, 68, 7501.3 ]	4271.1
[ 70, 950, 671, 6 ]	0