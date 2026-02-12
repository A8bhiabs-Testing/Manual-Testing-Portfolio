# Bug Reports – Login & Authentication

The following defects were identified during manual testing of the Trainline web application login functionality.

## Bug ID: BUG-001
**Title:** Login error message is unclear when invalid credentials are entered  
**Environment:** Web – Chrome (latest), Windows  
**Severity:** Medium  
**Priority:** Medium  

**Precondition:** User is on the login page

**Steps to Reproduce:**
1. Enter a valid registered email
2. Enter an incorrect password
3. Click the Login button

**Expected Result:**  
I should see an error message right away telling me the password is wrong.

**Actual Result:**   
An error shows up, but I actually missed it at first. It popped up at the very top of the form, and since I was looking at the button I just clicked, the error was "off-screen." I had to scroll up to find out what went wrong.


## Bug ID: BUG-002
**Title:** Login button is enabled when fields are empty
**Environment:** Web - Chrome (latest), Windows
**Severity**: Low
**Priority**: Low

**Precondition:** User is on the login page

**Steps to Reproduce:**
1. Click log in with empty fields

**Expected Result:** 
The login button shouldn't be clickable. It should stay greyed out (disabled) so the user knows they have to fill in the boxes first.

**Actual Result:**
The button is fully clickable even if I haven't typed anything. When I click it, it just stays on the page. It's confusing because it feels like the button isn't doing its job.
