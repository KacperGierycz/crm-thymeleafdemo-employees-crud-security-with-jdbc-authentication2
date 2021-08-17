# crm-thymeleafdemo-employees-crud-security-with-jdbc-authentication2

[link to live App on AWS](http://crmthymeleafsecurityjdbccrud-env.eba-fmwehpni.eu-central-1.elasticbeanstalk.com/showMyLoginPage?logout)

Crm/Employee... menagement tool is a base for many applications. It's a spring boot base app with a security layer
with list of employees/costumers to work on. The scope of usabilitis is authority dependent. Hosted on AWS.

* 3 Predefine Roles EMPLOYEE,MANAGER,ADMIN(logins on the login page:) setup with spring security defoult sql schemas(user,authorities) Bcrypted
* Login form is a custom form utilize a Thymeleaf to enable functions like csrf visuals with bootstrap.
* List of Employees/Customers is displayed with features according to a logged in user.
* DAO with JPARepository.  All the CRUD operations utilize be the service design pattern.
* The application can be develope into CRM/e-commerce/menagement tool. 

# What is it do
App welcoms with a login page and display a table of persons with their credentials.
There are 3 roles: employee who can see a list and serch for a specific name/surename, manager who can add and edit the specific credential, admin who can delete the record.


# What is it for 
It's now the employee menagement/crm application. The usability can be enchnced acording to desired buisenes needs.

# How is it work

