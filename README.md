# JPetStore DemoProject
  ## -Test Plan -


##### Revision History
| Date          | Description   | Author           | Comments     |
| ------------- | ------------- | ---------------- |--------------|
| 26.01.2024    | Test Plan  v01| Alina Raluca Ion   |versiunea 1.0 |
| 10.02.2023    | Test Plan v02 | Alexandra Sandulescu |versiunea 1.1 |

###### The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and aplly them in practice, using a live application

###### Application under test: [JPetStore Demo](https://jpetstore.aspectran.com/catalog/).
###### Tools used: Jira, Zephyr Squad.

###  1.	Introduction
The JPetStore Demo is an online pet store. Like most e-stores, you can browse and search the product catalog, choose items to add to a shopping cart, amend the shopping cart, and order the items in the shopping cart. You can perform many of these actions without registering with or logging into the application. However, before you can order items you must log in (sign in) to the application. In order to sign in, you must have an account with the application, which is created when you register (sign up) with the application.
This release will have have limited features. Over a period of time, new functionalities will be added to this site.


###  1.1	 Project Objective
We need to raise the trust in the quality of the project as high as possible before releasing it to customers.

Application under test:[JPetStore Demo](https://jpetstore.aspectran.com/catalog/).

[Documentation](https://jpetstore.mate.academy/jpetstore/help.html#SigningUp)


###  1.2	 Functionalities in scope

•	To design a user-friendly interface that allows customers to browse and search for products easily.

•	To provide photos for each product so the customers will know what they are gonna purchased.

•	To add a variety of pets so you can have from where to choose from.

•	Compatible with all most used browsers.



###   1.3 Functionalities and tests out of scope

•	Non-functional testing like stress, accessibility, performance is beyond scope of this project.

•	Automation testing is beyond scope.

•	All features that are not under Product Module

•	Automation testing is beyond scope.

###   2.	Test process

#### 2.1	Test planning

#####  Roles and responsibilities

•	Project manager – Elena Ionita

•	Product owner – Gabriel Ierbasu

•	Software developer – Vasile Popescu

•	QA Engineer – Alina Raluca Ion

#####  Entry criteria:

•	smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing).

•	testing environment is up and running.

•	roles and responsibilities for the project are allocated. 

•	functional business specifications are defined.

•	initial project risks were detected and mitigated.

•	test schedule is prepared.

•	the test plan must be created.

#####  Exit criteria:

•	100% of tests are executed.

•	90% of tests are passed.

•	no Critical defects have Open status.

•	no detected major risk remained un-mitigated.

•	User Add functionality tests are 100% passed.

•	all required documentation, including test plans, test cases, and test results, has been completed and reviewed.

#####  Risks:
•	stability risks (crashes, disconnects, etc).

•	IE browser might have performance issues.

•	Poor communication and collaboration between team members, stakeholders or external suppliers can lead to misunderstandings, delays, and rework.

•	stress conditions might impact the web application.

•	new browser might not be supported.

•	Budget Overruns: Unexpected expenses can strain the project budget, potentially requiring trade-offs in features or quality.



###  2.2 Test analysis 

Analyze the business requirements to make sure that we have all the details for creating the test conditions.
The testing process will be executed based on the above requirements for the Products module. 

The following test conditions were found:

	Verify if a new user can create an account in Sign Up without complete all the fields.

	Verify that the required/mandatory fields are marked with the ‘*’ symbol.

	Verify that if all fields are left blank an error message will be displayed.

	Verify that a validation message is displayed when an incorrect email format is used.

	Verify that the user cannot create an account by filling out only the email input field.

	Verify if a new user can create a password using just letters. 

	Verify if a new user who doesn’t have an account created, can Sign in with an email random 

	Verify that a registered user cannot create another account using the same email address.

	Verify that a new user can choose a language from the dropdown menu.

	Verify that a confirmation message or email is sent to the user after successful account creation.

	Verify that the user is able to change the number of items from the cart.

	Verify if the subtotal is getting changed when the user removes any item from the cart.

	Verify that the products remain in the shopping cart after the user close the browser and reopen the same site.

	Verify that images of products are displayed correctly.

	Verify that the prices are displayed correctly.

	Verify if you can add to the cart different types of animals.
 
	Verify if you add to the cart multiple products if the stock will show correctly if they have the product or the stock is empty.
	Verify that the user is redirected to the checkout page after clicking on the “Proceed to checkout “button.

	Verify that when a client attempts to buy a product without being logged in if they are redirected to the login page. 

	Verify that the user is able to proceed an order adding negative number like (-1,-2,-3….)

	Verify if you added 10 products to the cart, and delete 5 products, if the quantity are updated accordingly.

	Verify that production stock information is displayed.

	Verify if the cart is editable then check that the user is able to enter special characters.

	Verify that the user can add the same product in the shopping cart, after entering a negative value in the "Quantity “input field.

	Verify that Next Button and Cancel Button are available in the Checkout Address Page.

	Verify that Name, Street Address, City, State, Country, Postal code is the mandatory field in the Checkout Address page (Billing Address).
 
	Verify that if a client can cancel (delete) an order after placing it.   


###  2.3 Test design 

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are boundary value analysis, equivalence partitioning and use case testing.


The test cases with steps can be viewed here: [Test cases](https://github.com/AlinaRaluca92/Jira-Project-/blob/main/Test%20case%20report.pdf)


###  2.4	 Test implementation

•	All the test data is available and reviewed (test data= email examples, password examples, employee, user with admin role)

•	This test run includes only regression testing in which we will run tests that have the highest priority, this will be main priority.

•	Create the test suites (Cycle Summary) (grouped by release version or testing type)

###   2.5	 Text Execution 

•	The tests will be executed on the latest versions of browsers: Chrome, Mozilla Firefox, IE. If time will be available, we will extend tests on other browsers. 

•	Bugs (defects) will be created based on the failed test cases.

•	The full regression testing will be done after new application changes.

•	Retesting will be done after a bug fix .


###   2.6	 Test closure 

•	at least 90% of tests are passed.

•	no Critical issues have Open status.

###   2.7	 Test monitoring and control

•	Status reports will be generated to reflect the current status of testing process.

•	In case of major problems, control measures will be taken. 

##  3.	Test deliverables  

![daily test execution progress](https://github.com/AlinaRaluca92/Jira-Project-/assets/161631059/aa526537-d312-45fe-af02-335a383a62a5)

![test execution](https://github.com/AlinaRaluca92/Jira-Project-/assets/161631059/364fc34d-8c91-463d-9b27-689a982de6e7)

![Traciabilit](https://github.com/AlinaRaluca92/Jira-Project-/blob/main/traciability%20matrix.JPG)





