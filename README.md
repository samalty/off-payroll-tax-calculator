# Off-Payroll tax calculator

This is a tax calculator, designed to help UK contractors and freelancers determine the financial impact of the Off-Payroll legislation on 
their post-tax income. The Off-Payroll legislation is due to be introduced to the private sector in April 2020, and will deem hiring 
firms responsible for assessing the employment status of their flexible workers for tax purposes.

## How it works

Provided with a form, the user is invited to input their daily contract rate and an estimate of the expenses that they claim annually. In 
response, the application performs a number of calculations, resulting in a comprehensive breakdown of their tax liabilities and post-tax 
income when 'inside IR35' (i.e. deemed within scope of the Off-Payroll legislation) and 'outside IR35' (outside the scope of the 
Off-Payroll legislation).

The output also includes a table comparing the total tax liability and post-tax earnings from either arrangement to help the user determine 
the most favourable outcome. Generally, this will be operating 'outside IR35', although once a contractor reaches a certain earnings 
threshold it actually becomes more favourable to be subject to employment taxes.

The calculator manipulates the active state of certain elements based on the live form input, such as the user's gross earnings, while 
other elements are altered once the form is submitted. There are also some inline ternary operators included in the JSX to determine the 
state of certain conditional CSS elements.

## Technologies used

- The *React* framework was used to facilitate the application's dynamic user interface.
- *JavaScript* was used to perform the various calculations, while inline JS was also used to determine the status of conditional CSS 
elements.
- *HTML* was used to structure the website and *CSS* to enhance the appearance.

## Try it out

This application is live at: https://samalty.co.uk/off-payroll-tax-calculator/
