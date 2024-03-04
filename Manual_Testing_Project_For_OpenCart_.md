<h1>Testing Project for **Opencart** </h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **Opencart**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories were created in Jira and describes the functional specifications of the "Wish list" , "Seach box", "What to do next?", "Products list" and "Checkout" modules, for which the final project is performed upon.

[Wish List.pdf](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/files/14461902/Wish.List.pdf)

[Search box.pdf](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/files/14461901/Search.box.pdf)

[What to do next.pdf](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/files/14461900/What.to.do.next.pdf)

[Products list.pdf](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/files/14461899/Products.list.pdf)

![Checkout Button](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/assets/160262559/61038d77-0df1-4f40-ab4a-78110260351d)


Here you can find the release that was created for this project:

![Release](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/assets/160262559/8bbc61ee-b3ee-4fe1-8b0b-001e521d18c3)

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the Opencart application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here [Test Plan - Opencart.docx](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/files/14480880/Test.Plan.-.Opencart.docx)


<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

<ul>
  <li>Project manager: Narcis Dumitrescu</li> 
  <li>Product owner: Pop Alexandru </li>
  <li>Software developer Sirbu Matei </li>
  <li>QA Engineer: Racea Alin</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

- It is necessary to have a thorough understanding of the application flow.
- Smoke test passed 
- Testing environment is up and running
- Potential project risks are detected and mitigated
- Relevant data, such as user profiles, discount voucher codes, and credit card informations should be prepared and available for testing

<h4> 1.1.3 Exit criteria defined </h4>


- The test plan document must be completed.
- 95% of tests are passed
- No Critical issues have Open status
- Update tests are 100% passed (update tests will not generate other new issues that impact the application))

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

- For **Shopping cart module** the functionalities in scope are related to the accesibility of the user to edit and submit an order by choosing the quantity of products, the payment and delivery methods and by filling the delivery informtions and the discount code boxes.
- For **The header module** the functionalities in scope are related to accesibility of the user to search and add products to wishlist
- Throughout the testing process we will perform functional testing and some types of non-functional testing (like usability testing), positive testing and negative testing and also, as needed, we will perform retesting and regression testing. 
- Some other types of testing that might be performed if necessary are smoke testing and sanity testing. 

<h5>Tests not in scope: </h5>

- All the other modules, except "Shopping cart" and "The header" modules will not be tested throughout this project.
- For "The header" module we will not test the "Shopping cart" and "Checkout" buttons because we will already test them in the previous module.
- Being a demo web application, the performance and security testing is out of scope for this project

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

- The team's lack of experience
- Difficulties in understanding the bussines requirements
- Delays in testing process caused by the testing environment not being ready in time
- Delays caused by the lack of personnel

<h5> Product risks: </h5>

- Stability risks (crashes, disconnects, etc)
- Malfunction when the PHP settings are not properly turned on
- Safari browser might slow down the application
- The web page pagination could be impacted when opened on mobile devices
- Stress conditions might impact the web application
- New browser might not be supported

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control</h3>
  
- We will have daily test status report which should also include the notification of any deviation from the plan
- Keeping an eye on resource allocation and utilization
- Checking the schedule and timeline is on track
  By implementing these monitor and control activities we have visibility into whether the testing is on track, whether the quality goals are being met, and whether any corrective actions are required to ensure successful project outcomes
  
![Screenshot 2024-02-16 200420](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/assets/160262559/4bd45a5d-8c6b-4d60-85f7-82f6d36ab58a)

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <br><br>

The following test conditions were found: <br>

![Tests list](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/assets/160262559/f9727c49-cb2b-4b5c-a18d-52541c6fff45)

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here [TestCases.pdf](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/files/14469842/TestCases.pdf)


<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

-	All the test data is available and reviewed (test data= email examples, password examples, different type of currency, different types of credit cards)
-	Test environment is validated through smoke testing.
-	We make sure that all the test data are created (test data= user and password examples, voucher code examples, different types of credit cards)
-	we prioritize the tests based on risks and business priority

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: OpenCart-v1-tests

Bugs have been created based on the failed tests. The complete bug reports can be found here: ![Bugs list](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/assets/160262559/da609087-4d5f-4b2d-a9dd-4a0112874f69)

The following is a summary of the bugs that have been found

- When clicking on the product image the image size is not increasing (severity - major;  priority - low)
- When typing text in the quantity box we are not receiving an error message (severity - minor;  priority - low)
- The valid coupon code is not working (severity - critical; priority - medium )
- Shipping method drop down button can not be clicked (severity - blocked; priority - high)
- Payment method rubric can not be clicked (severity - blocked;  priority - high)
- An error message is not displayed when putting numbers in the Last/First Name text box (severity - minor; priority - low)
- Search Box returns an error page (severity - critical; priority - high)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here:  ![Tracebility Matrix](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/assets/160262559/e163ca95-5e88-4d77-a72b-d766cd84f3d8)

Test execution chart was generated and can be found below. 

![Screenshot 2024-02-16 201202](https://github.com/alyn232/Manual_Testing_Project_For_opencart.md/assets/160262559/0af46721-829f-46e5-b612-d9628e427011)

The final report shows that a number of 7 tests have failed of a total of 13

A number of 7 total bugs were found, from which the priority is: 2 are high and 4 are medium.

In conclusion, a number of 13 tests were created and executed which cover 60% of the tests in scope. The aplication is not stable enough to go to production because we found critical errors that don't allow the user to complete an order, namely the payment and shipping methods can't be clicked. Also, we were not able to fully test the "Search" and "Wishlist" functionalities due to lack of time.
My recomandation is that we can exclude the "Shopping cart" and "Checkout" buttons from the header, because we already have a big "Shoping cart" button near the one that it is in the header and when we click this button we are redirected into a page that also contain "Checkout" button.


