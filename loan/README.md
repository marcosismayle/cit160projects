The user interfaces for a loan calculator. Figure 9-7: The user interfaces for a loan calculator. In a file named loan.html, write an HTML document that looks similar to figure 9-7 in the textbook. Write four functions with these headers:

    function doPayment ( )
    function doBalance ( )
    function computePayment (principal, annualRate, years, periodsPerYear)
    function computeBalance (principal, annualRate, years, periodsPerYear, numberOfPaymentPaidToDate)

The first two functions (doPayment and doBalance) do the following:

    a. Take no parameters.
    b. Are called from an onclick attribute.
    c. Get input from the user.
    d. Call the computePayment or the computeBalance function.
    c. Display a result to the user.

The computePayment function computes and returns the monthly payment for a loan with a fixed annual interest rate. The formula for computing a loan payment is

    p =  ar/1 − (1 + r)−n

Where p is the payment per period, a is the loan amount, r is the interest rate per period, and n is the total number of periods throughout the life of the loan.

The computeBalance function computes and returns the balance for a loan with a fixed annual interest rate. The formula for computing the balance of a loan after d payments have been made is

    b = a (1 + r)d −  (p ( (1 + r)d − 1 ))/r

Where b is the balance or payoff amount, a is the loan amount, r is the interest rate per period, p is the payment per period, and d is the number of payments paid to date.