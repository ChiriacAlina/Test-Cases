# Test-Cases
**Test case 1**

Title: Check if the research will bring you results

Description: Check if the search case will give to the user any suggestion for the products related to his wish.

Steps to reproduce:

    Go to the search button

    Write the name of the product to be found

    See if there are any suggestion for the product

Expected results: The user should receive at least one product from the research.

Test data: Radio, phone

------------------

**Test case 2**

Title: Auto-fill of the name for the product written in the search

Description: The product written in the search should auto-fill after at least 4 letters if there are not any other suggestions.

Steps to reproduce:

    Go to the search button

    Write a product name with 4 letters

    See if you receive the auto-filled name

Expected results: Receive the list of the product named.

Test data: boxa

----------

**Test case 3**

Title: No error for the product not found in the search button

Description: If the user will write a product and is not found in the list, he should not receive an error but an alert with "0" results on the website.

Steps to reproduce:

    Go to the search button

    Write an nonexistent product

    Se if an error appear

Expected results: To receive an alert that the product is not on the website instead of an unknown error.

Test data: boxxxxx

-------------

**Test case 4**

Title: Login with correct credentials

Description: Check if the login works when user enters the correct credentials.

Steps to reproduce:

    Open website website,com/login

    Add correct user pass

    Click login button

Expected result: User should be able to login and redirected to his profile page.

Test data: User: alina & pass: 123

Pre-conditions: User should have an valid account.

--------------

**Test case 5**

Title:Test login with no credentials

Description: Check if the login works when a person use no credentials.

Steps to reproduce:

    Go to website.com/login

    Enter no credentials

    Press login button

Expected results: User should not be able to login on the website and should receive an error alert.

Test data: no credentials


