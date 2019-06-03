# Multi-step React Form

*State:* 
Steps and fields

- Step is of type number, and has initial value = 1
     - *Example:* FormUserDetails is step 1, FormPersonalDetails is step 2 etc.
- Fields are form fields like firstName, lastName etc.

*Methods:*
    - nextStep() => increments step
    - prevStep() => decrements step 
    - handleChange() => when data is added inside input fields and it updates `fields` of state.

## Components:
- UserForm
    - FormUserDetails
    - FormPersonalDetails
    - Confirm
    - Success
