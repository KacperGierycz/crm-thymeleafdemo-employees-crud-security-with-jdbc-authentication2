# crm-thymeleafdemo-employees-crud-security-with-jdbc-authentication2

[link to App on AWS](http://crmthymeleafsecurityjdbccrud-env.eba-fmwehpni.eu-central-1.elasticbeanstalk.com/showMyLoginPage?logout)

Crm/Employee... menagement tool is a base for many applications. It's a spring boot base app with a security layer
with list of employyes/costumers to work on. The scope of usabilitis is authority dependent. Hosted on AWS.

* 3 Predefine Roles EMPLOYEE,MANAGER,ADMIN(logins on the login page:) setup with spring security defoult sql schemas(user,authorities) Bcrypted
* Login form is a custom form utilize a Thymeleaf to enable functions like csrf visuals with bootstrap.
* List of Employees/Customers is displayed with features according to a logged in user.
* DAO with JPARepository.  All the CRUD operations utilize be the service design pattern.
* The application can be develope in many directions easly. 



