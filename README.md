# CypressUITestingFramework-WebStorm #
---------------
:octocat: A Cypress :tangerine: testing framework which runs few tests which put to test different UI aspects of the following websites:
https://rahulshettyacademy.com/angularpractice/  
https://rahulshettyacademy.com/AutomationPractice/  
http://www.qaclickacademy.com/  

## DESCRIPTION ##
The test scripts were not built based on a set of specific test cases. They were designed to learn and to test specific aspects of the websites, giving ample scope to leverage the multiple features of Cypress.

Because Cypress can be used both HTML and Angular pages, we have taken into consideration both the websites and build the test scripts accordingly.

The framework has used the following tools for handling the many aspects of testing and reporting:
* Cypress
* GitHub
* Jenkins
* jQuery
* Cypress Dashboard
* WebStorm
* JavaScript
* Chai
* Mocha

The testing framework tests of 5 pages of different websites. They are:
1. AngularHomePage
2. AngularShoppingPage
3. Automation Practice Page Test I
4. Automation Practice Page Test II
5. Home Page Test

The Automation Practice Page aspect of the respective website contains a lot of test information and hence, it was decided to split it into two different test scripts.

We will deep-dive into what the respective page files test below:

#### 1. AngularHomePage ####
This complete test file consists of two tests on the https://rahulshettyacademy.com/angularpractice/ webpage which is referred to as the Angular Home Page:
* ***Angular Home Page: Header***
This test script verifies if the header of the webpage consists of "ProtoCommerce", "Home" and "Shop" links
* ***Angular Home Page: Form***
This test script fills the form in the webpage with the required information and verifies if submitting the information throws an alert saying "Success"

#### 2. AngularShoppingPage ####
This complete test file consists of two tests on the https://rahulshettyacademy.com/angularpractice/ webpage, but because this test script is mostly concerned with testing the shopping aspect of the webpage, this is referred to as the Angular Shopping Page:
* ***Home Page Verification***
This test script also verifies the form in the Home Page. But what this does is it uses abstraction to handle the data present in the test script. The test finally verifies that the Entrepreneur button is disabled in the page
* ***Shopping Test***
This test script selects the 'Blackberry' and 'Nokia Edge' phones from the shopping catalog and adds them to the cart. The selection is made by saving the logic of adding the phones to cart by using a function called "selectProduct()". This function is called and the names of the phone brands are given as the input.
* ***Cart Item Verification***
This test script verifies that the items in the cart are present and that the individual costs of the items in the cart are adding up to the Total Cost calculated in the webpage
* ***Cart Checkout Test***
This test script enters the delivery location, makes the purchase and verifies the Success Alert message

#### 3. Automation Practice Page Test I ####
This complete test file consists of seven tests on the https://rahulshettyacademy.com/AutomationPractice/ page which is referred to as the Practice Page:
* ***Automation Practice Page Header***
This test script verifies the functionality of the header of the Automation Practice page by also verifying the links to 'Home', 'Practice', 'Login' and 'Signup' pages
* ***Radio Button Example Functionality***
This test script, along with verifying the title of the 'Radio Button Example', selects radio buttons and verifies that the action has been committed
* ***Dropdown Functionality: Suggestion Class Example***
This test script, along with verifying the title of the 'Suggestion Class Example', enters the text 'Ven', selects 'Venezuela' from the dropdown options and verifies that the text is present in the textbox
* ***Dropdown Functionality: Dropdown Example***
This test script, along with verifying the title of the 'Dropdown Example', selects Option1 and verifies that the dropbox text is 'Option1'
* ***Checkbox Functionality***
The test script, along with verifying the title of the 'Checkbox Example',  checks a few checkboxes and verifies that they have been checked  
* ***Switch Window Functionality***
This test script, along with verifying the title of the 'Switch Window Example', verifies that clicking on the 'Open Window' button triggers the 'openWindow()' function
* ***Switch Tab Functionality***
This test script, along with verifying the title of the 'Switch Tab Example', verifies that clicking on the 'Open Tab' button opens a new tab with the required URL

#### 4. Automation Practice Page Test II ####
This complete test file consists of seven tests on the https://rahulshettyacademy.com/AutomationPractice/ page which is referred to as the Practice Page:
* ***Switch To Alert Functionality: Part I***
This test script, along with verifying the title of the 'Switch To Alert Example', verifies that entering the required text in the textbox and clicking on the 'Alert' generates the respective popup with the respective information
* ***Switch To Alert Functionality: Part II***
This test script verifies that entering the required text in the textbox and clicking on the 'Confirm' generates the respective popup with the respective information
* ***Web Table Example: Part I***
This test script, along with verifying the title of the 'Web Table Example', verifies that the cost of a certain course in the web table matches the expected value
* ***Web Table Example: Part II***
This test script verifies that the addition of the costs of a few courses in the web table is matching the expected value
* ***Element Displayed Example***
This test script, along with verifying the title of the 'Element Displayed Example', verifies that clicking on the 'Hide' and 'Show' options results in the respective actions being performed on the text box
* ***Mouse Hover Example***
This test script, along with verifying the title of the 'Mouse Hover Example', verifies that performing the hovering action on the 'Mouse Hover' button and clicking on the 'Hide' or 'Show' options results in the webpage undergoing the respective changes
* ***Handling frames***
This test script verifies that the iframe in the web page contains the 'Mentorship' section and that the size of a certain element is 2

#### 5. Home Page Test ####
* ***Closing Alert***
* ***Handling Title Text***
* ***Alert Subscription***
* ***Email Subscription Test***
