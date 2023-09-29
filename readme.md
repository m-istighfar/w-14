# Project 

## Live Deployment

- [Netlify](https://superlative-bublanina-a7be24.netlify.app/)


## Scenarios

### 1. Login Page

- **Rendering:** Ensure that the login page is rendered correctly.
- **Unit Test:** \
   a. Verify that the page title "Sign in to your account" is correctly rendered.\
   b. Confirm that the logo is correctly rendered using `getByAltText('logo')`.\

   ![1](./src/assets/images/1.png)

   c. Ensure that the labels "Your email" and "Password" are rendered correctly.\
   d. Validate that the "Sign in" button is rendered and working correctly, confirming form submission.\
   e. Ensure no unit tests fail.

   ![2](./src/assets/images/2.png)

### 2. Register Page

- **Rendering:** Confirm that the register page is displayed accurately.
- **Unit Test:** \
   a. Verify that the page title "Create your account" is correctly rendered.\
   b. Confirm that the logo is correctly rendered.\

   ![3](./src/assets/images/3.png)
   
   c. Ensure that the labels "Name", "Your email", and "Password" are rendered correctly.\
   d. Validate that the "Register" button is rendered and working correctly, confirming form submission with the correct data.\
   e. Ensure no unit tests fail.

   ![4](./src/assets/images/4.png)

### 3. Category Page

- **Rendering:** Make sure the category page renders as expected.
- **Unit Test:** \
   a. Ascertain no unit tests fail.\
   b. Ensure unit tests can detect the table, validating the rendering of table headers and checking the data populated in the table.\

   ![5](./src/assets/images/5.png)

   c. Confirm that the `CategoryModal` component is rendering correctly with the initial values and that the "OK" and "Cancel" buttons function as expected.\
   d. Validate that the `handleOk` and `setFormValues` functions are called with the correct values and that the `handleCancel` function works correctly.\

   ![6](./src/assets/images/6.png)

### 4. Profile Page

- **Rendering:** Ensure that the profile page is rendered correctly.
- **Unit Test:** \
   a. Confirm the title "Profile Page" is correctly rendered.\
   b. Validate the rendering of profile data after a successful fetch from the backend.\
   c. Verify that user data, including ID, Name, and Email, are correctly rendered.\
   d. Ensure no unit tests fail.

   ![7](./src/assets/images/7.png)
