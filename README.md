# Test Cases

**These are some Test Case Samples that I wrote.**

------------------------------------------------------------------------------------------

**Description:** Check if the login works when a person uses a correct user and password.

**Steps to reproduce:**

1. Go to www.somewebsite.com/login

2. Enter user and password

3. Click Login button

**Expected result:** Login should be successful

**Test data:** User:mada Password:1234567

------------------------------------------------------------------------------------------

**Description:** Check if the show/hide password button works when a person writes a password.

**Steps to reproduce:**

1. Go to www.somewebsite.com/login

2. Enter a password

3. Click on visibility eye icon

**Expected result:** Password should be visible

**Test data:** Password: 1234567

-------------------------------------------------------------------------------------------

**Description:** Check if forgot password functionality works as expected and an email with reset password link is sent.

**Steps to reproduce:**

1. Go to www.somewebsite.com/login

2. Click "Forgot Password" button

3. Add an email adress

4. Press "Recover" button

**Expected result:** User should receive an email with a reset password link. That link should allow the user to create a new password.

**Test data:** User: mada@email.com

**Note** Please check the login again after running this test case.

--------------------------------------------------------------------------------------------

**Description:** Check if an error message appears when a person uses an invalid user.

**Steps to reproduce:**

1. Go to www.somewebsite.com/login

2. Enter an invalid user 

3. Click Login button

**Expected result:** A message appear "Please enter a valid email adress".

**Test data:** User: invalidemail@mail.com

