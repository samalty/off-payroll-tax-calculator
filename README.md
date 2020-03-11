# Off-Payroll Tax Calculator

This is a tax calculator, designed to help UK limited company ontractors and freelancers determine the financial impact of the 
Off-Payroll legislation on their post-tax income. The Off-Payroll legislation is due to be introduced to the private sector in April 
2020, and will deem hiring firms responsible for assessing the employment status of their flexible workers for tax purposes. This 
application was built using React and takes advantage of the framework's interactive UI capabilities.

## How it works

Provided with a form, the user is invited to input their daily contract rate and an estimate of the expenses that they claim annually. 
In response, the application performs a number of calculations, resulting in:

- A comprehensive breakdown of the user's income and tax liabilities while operating 'outside IR35' (including corporation tax, income tax and combined tax liabilities, and annual and monthly post-tax income)
- An equivalent breakdown of the user's income and tax liabilities when deemed to be 'inside IR35' (including income tax, national insurance and combined tax liabilities, and annual and monthly post-tax income)
- A table comparing the total tax liability and post-tax earnings from either arrangement

React's interactive UI capabiities are used as the calculator manipulates the active state of certain elements based on the live form 
input, such as the user's gross earnings, while other values are updated once the user has submitted the form. The JSX also includes 
some inline ternary operators to determine the state of certain conditional CSS elements.

## Technologies used

- The *React* framework was used to facilitate the application's dynamic user interface
- *Javascript* was used to perform the various calculations, while inline JS was also used to determine the status of conditional CSS elements
- *HTML* was used to structure the website and *CSS* to enhance the appearance

## Try it out

This application is live at: https://samalty.co.uk/off-payroll-tax-calculator/
