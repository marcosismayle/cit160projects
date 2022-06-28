The user interfaces for an investment calculator.Figure 9-6: The user interfaces for an investment calculator. In a file named invest.html, write an HTML document that looks similar to figures 9-6 in the textbook. Write two functions with these headers:

    function doFV ()
    function computeFutureValue(principal, annualRate, years, periodsPerYear)

The first function (doFV) does the following:

    a. Takes no parameters.
    b. Is called from the onclick attribute.
    c. Gets input from the user.
    d. Calls the computeFutureValue function.
    e. Displays the result to the user.

The second function (computeFutureValue) computes and returns the future value of an investment. The formula for computing the future value of an investment is

    f = a (1 + r)n

Where f is the future value, a is the investment amount sometimes called the principal, r is the growth rate per period, and n is the total number of periods throughout the life of the investment.

