# Multi-step React Form

### What to include in state?
- Steps
- Fields

> Explanation:
- Step is of `type number`, and has `initial value = 1`
     - *Example:* FormUserDetails is step 1, FormPersonalDetails is step 2 etc.
- Fields are form fields like firstName, lastName etc.

### Methods used inside the react component?
   - nextStep() => increments step
   - prevStep() => decrements step 
   - handleChange() => when data is added inside input fields and it updates `fields` of state.

## Components:
- UserForm
    - FormUserDetails
    - FormPersonalDetails
    - Confirm
    - Success
