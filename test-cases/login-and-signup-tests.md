# Login & Signup Test Cases

## Test Case 1
**Title:** Login with valid credentials  
**Precondition:** User has a registered account  
**Steps:**
1. Open login page
2. Enter valid email "test_user@example.com"
3. Enter valid password "<valid_password>"
4. Click Login
**Expected Result:** User is redirected to dashboard

## Test Case 2
**Title:** Login with invalid password  
**Precondition:** The system has a registered user with a valid email
**Steps**
1. Open login page
2. Enter valid email "test_user@example.com"
3. Enter valid password "<pass@123>"
4. Click login
**Expected result:** User gets a pop-up saying please check your details and try again.

## Test Case 3
**Title:** Leaving a field empty
**Precondition:** The trainline home page is loaded and the sign in button has been clicked
**Steps:**
1. Without entering any details in the blank fields hit login
**Expected result:** "Please enter an email address" should show in red font just below the email ID field and "Please enter a password" should show in a red error nessage just below the password field.

## Test Case 4
**Title:** Login with incorrect email ID
**Precondition:** The trainline home page is loaded and the sign in button has been clicked
**Steps:**
1. Enter an invalid email "test_user@example.com"
2. Enter valid password "Valid_password"
3. Click log in
**Expected result:** "Please check your details again" error message should be shown.

## Test Case 5
**Title:** Verify the "Forgot password" link redirects to the Password Reset page
**Precondition:** The trainline home page is loaded and the sign in button has been clicked
**Steps:**
1. Click the "forgotten password" link on the screen.
2. Enter a valid email "test_user@example.com"
3. Click continue
**Expected result:** A page loads with an email has been sent to your account to reset password.
...

