Top 18 interview questions for salesforce jobs.
Thanks to Deepakah for compiling the list.

Question 1) What is Salesforce??

Answer: Salesforce is a company founded by Marc Benioff. Revenue of the company comes from a cloud-based CRM tool also referred as Salesforce CRM.

 

 Question 2) What is Sandbox???

Answer: Sandbox is a copy of production database. Before making any changes in the production, the changes are first tested in Sandbox and if the test cases are successful then we deploy these new changes in production.

 

Question 3) What are different types of Sandboxes???

Developer Sandbox
Developer pro-Sandbox
Partial data Sandbox
Full copy sandbox
 

Question 4) What is a Full copy Sandbox??

Answer: Full copy sandbox is an exact replica of the production. You can copy configuration as well as real-time data from production. Refresh time interval for Full Copy Sandbox is 29 days.

 

Question 5) What is the difference between ISBLANK () AND ISNULL ()?

Answer: ISNULL () works only for number data type fields, when there is no value provided for the number fields, it returns true.

ISNULL () won’t support TEXT data type fields because text fields can never be Null.

ISBLANK () supports numeric as well as text data types.

 

Question 6) What is the architecture of the salesforce?

Answer: Salesforce follows MVC –Model, View and Controller architecture.

View – stands for user interface (Apps, Tabs, Page Layouts, Fields and Record Types)

Controller – stands for Business Logic (Save, Edit, New, Cancel and Delete – what action or logic to perform on click of these buttons is provided in Controller)

Model – It is the Database, which stores Schema (Meta-Data (Data about Data) –> Apps, Tabs, sObjects, fields, Apex Classes, Visualforce pages, etc…) and Instance (Records)

 

Question 7) What is the difference between 15 digit and 18 digit id in Salesforce?

Answer: Every record in Salesforce has a unique identifier also called as id. You can check record Id in the URL bar of that particular record.

This is  15 digits unique case-sensitive id. First three characters represent the object. So the records which belong to the same object will have first three digits same.

But if the user access the existing records through API (either from query tool or a program), it will return 18 digits id, which is  case- insensitive.

Last 3 digits of the 18-digit represent the checksum of the capitalization of 15 digit id.

 

Question 8) What is Out of the box functionality???

Answer: The functionality that comes with standard Salesforce without writing to code is called as out –of the box functionality.

 

Question 9) What are Governor Limits???

Answer: Since salesforce works in a multitenant environment. There are some limits we need to follow which are also called as Governor Limits.

Number of fields per object: 500

Number of Master-detail relationship per object: 2

Maximum Number of Lookup relationship on object: 25

Maximum number of rollup summary fields:  25

How many external ids we can enable for an object: 7 (increased from 3 to 7 after winter -15 release)

 

Question 10) What is Production ? and What is production URL?

Answer: We should not make any code changes directly in production because end-users are using the application from the production environment. If we make code changes directly to production without doing complete testing, it might crash production environment and end-users will get affected. Production Url is: login.salesforce.com

 

Question 11) What are Activities in Salesforce?

Answer: In order to create activities on an object, we must check for “Allow Activities” checkbox, if Allow Activities checkbox is checked then the user can add open Activities and Activity History related lists on the Object layout.’

There are two types of activities:

Task : Task is nothing but work assigned to a particular person.

Event: has a certain time limit.During that time, individuals should assemble and after the time limit is over, the event will get complete.

 

Question 12)How to Rename the tab?

Answer: Tab name is derived from the Plural label field on the custom object. In order to rename, go to the corresponding object detail page and rename the plural label.

Question 13) What are the different type of tabs available in Salesforce?

Answer: We have three different types of tabs :

   Custom tabs( created for object)
   Web Tabs ( created to display a website)
   Visualforce Tabs ( created to display Visualforce page)
 

Question 14) Is it possible to delete a user in salesforce?

Answer: No, we can not delete a user record in Salesforce. We can only deactivate the user record.

 

Question 15) What is the maximum batch size of data loader?

Answer: 10,000 records and minimum size of 1 record.

 

Question 16) Scenario: There are two workflow rules on the same object say namely workflow1 and workflow2. If workflow1 fires then a field will be updated on the same object, if the field updated and due to this workflow2 criteria meets then what will happen, workflow2 will fire or not?

Answer: No, it won’t fire. To fire workflow2 we should enable “Re-evaluate Workflow Rules” checkbox on the workflow 1.

Question 17)What are different types of Reports available in Salesforce?

Tabular Report (Displays records in a form of table)
Summary Report (summarize the information based on certain fields)
Matrix Report ( summarize the information in two-dimensional manner, both rows vise, and columns vise)
Join Report ( summarize information in different blocks on the same object and the related objects)
 

Question 18) How many blocks can we create for join reports?

Answer:5 blocks

TAGS: SALESFORCE
Read more articles
