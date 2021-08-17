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
There are 3 roles: employee who can see a list and serch for a specific name/surename, manager who can add form with custom validation and edit the specific credential, admin who can delete the record.


# What is it for 
It's now the employee menagement/crm application. The usability can be enchnced acording to desired buisenes needs.

# How it works

1. Levereaging Spring boot capabilities in configurating moodules in easiest way all Java config no xml. 
2. Spring security (JDBC) to configure the ROLES.
3. Database SQL 3 tables: 1 for employees data, 2&3 setup for spring security bcypt pattern.
4. Two datasources configured in properties security and employees.
5. Spring Data JPA is mapping the SQL to entieties employee.
6. DAO is uses JPARepository no need to manage transacions, connections.
7. Utilize the service layer interface design pattern with gives flexibility to future development. 
8. Thymeleaf Security to take care of login form, csrf, buttons displaying acording to autorieteies.
9. Validation of form for new/edit custom validation for e-mail.
10. Java MVC techology to manage requests and models.
11. Maven to manage a Dependencies.
12. Jar file is deployed on AWS Elastic Beanstalk and database on Amazon RDS

[Enjoy the live app](http://crmthymeleafsecurityjdbccrud-env.eba-fmwehpni.eu-central-1.elasticbeanstalk.com/showMyLoginPage?logout)

 
