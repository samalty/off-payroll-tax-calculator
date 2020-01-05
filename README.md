# Off-Payroll Tax Calculator

This is a calculator built to help contractors understand the financial impact of the Off-Payroll Working Rules on their income. The legislation introduces changes to the tax treatment of some limited company contractors and is due to be implemented in April 2020. This application was built using React and takes advantage of the framework's interactive UI capabilities.

## How it works

The calculator invites the user to enter their daily contract rate and an estimate of the annual expenses that they claim via a form, returning a number of calculations upon the submittal of this form.

The feedback provided includes:

- A detailed breakdown of the user's income and tax liabilities while operating 'outside IR35' (including corporation tax, income tax and combined tax liabilities, and annual and monthly post-tax income)
- A detailed breakdown of the user's income and tax liabilities when deemed to be 'inside IR35' (including income tax, national insurance and combined tax liabilities, and annual and monthly post-tax income)
- A table providing a side-by-side comparison of the two outcomes

React's interactive UI capabiities are used to update the state of certain variables as the user enters values into the form. Other values are updated once the user has submitted the form, which calls on a function containing separate algorithms for the 'inside IR35' and 'outside IR35' calculations.

## Technologies used

- React: This application was developed using the React framework
- JavaScript: Javascript logic was used to build the algorithms performing the tax calculations
- CSS: CSS was used to enhance the appearance of this application

## Try it out

This application is live at: https://samalty.co.uk/off-payroll-tax-calculator/
