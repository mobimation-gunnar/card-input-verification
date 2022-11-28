## Assignment comments
The delivered assignment result claims to
represent an example of credit/debit card
input formatting and validation functionality
in the form of a Javascript React application.

The code makes use of reusable components
where applicable, and where I can the describe
the functionality of all part that implements
the solution.

### Re-used components
There are two major re-used components,
"payment" and "react-credit-cards".
where I did work to improve on the code
and also added one card provider as a demo
of extending existing code.

### Card data input validation
Existing re-used code supports formatting
of values at time of input and do not offer any
integration with any payment provider for online
card verification.
Form input formatting assures that
* a certain number of characters are input for a field  
  as required for that field. Form does not allow  
  pressing Submit until all such condition as met. 
* String or Numeric format enforced according to each field.
* Expiration date test.  
As convention the Expiration Date for a new card is 3 years.  
 So I added a test that checks expiration date is a maximum  
 of three years forward from current day.
