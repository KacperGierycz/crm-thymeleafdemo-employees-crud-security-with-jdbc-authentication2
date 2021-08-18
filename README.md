# crm-thymeleafdemo-employees-crud-security-with-jdbc-authentication2

[link to live App on AWS](http://crmthymeleafsecurityjdbccrud-env.eba-fmwehpni.eu-central-1.elasticbeanstalk.com/showMyLoginPage?logout)

CRM/Employee... management tool is a base for many applications. It's a spring boot basses app with a security layer
with a list of employees/customers to work on. The scope of usability is authority-dependent. Hosted on AWS.

* 3 Predefine Roles EMPLOYEE,MANAGER,ADMIN(logins on the login page:) setup with spring security defoult sql schemas(user,authorities) Bcrypted
* Login form is a custom form that utilizes a Thymeleaf to enable functions like csrf visuals with bootstrap.
* List of Employees/Customers is displayed with features according to a logged-in user.
* DAO with JPARepository.  All the CRUD operations utilize to be the service design pattern.
* The application can be developed into CRM/e-commerce/management tool. 

# What is it do
The app welcomes with a login page and displays a table of persons with their credentials.
There are 3 roles: an employee who can see a list and search for a specific name/surname, a manager who can add a form with custom validation and edit the specific credential, the admin who can delete the record.


# What is it for 
It's now the employee management/CRM application. The usability can be enhanced according to desired business needs.

# How it works

1. Leveraging Spring boot capabilities in configuration modules in the easiest way all Java config no XML. 
2. Spring security (JDBC) to configure the ROLES.
3. Database SQL 3 tables: 1 for employees data, 2&3 setup for spring security bcypt pattern.
4. Two data sources configured in properties security and employees.
5. Spring Data JPA is mapping the SQL to entities employees.
6. DAO has used JPARepository no need to manage transactions, connections.
7. Utilize the service layer interface design pattern with gives flexibility to future development. 
8. Thymeleaf Security to take care of login form, csrf, buttons displaying according to authorities.
9. Validation of form for new/edit custom validation for e-mail.
10. Java MVC technology to manage requests and models.
11. Bootstrap is a template for visuals cuteness.
12. Maven to manage a Dependencies.
13. Jar file is deployed on AWS Elastic Beanstalk and database on Amazon RDS

[Enjoy the live app](http://crmthymeleafsecurityjdbccrud-env.eba-fmwehpni.eu-central-1.elasticbeanstalk.com/showMyLoginPage?logout)

 
