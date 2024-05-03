In this repository, you'll find a Java project that demonstrates the implementation of Spring Boot and Spring MVC Security for building secure web applications with role-based access control. The project integrates with a MySQL database to manage user authentication and authorization.

Key features of this project include:

    User Authentication: Utilizing Spring Security, usernames and encrypted passwords (using BCRYPT) are securely retrieved from a MySQL database.

    Role-Based Access Control: Users are assigned different roles (such as Managers, Admins, and Employees), each with specific access permissions to different parts of the application.

    Web Pages and Permissions:

        Login Page: Users authenticate through a login page where incorrect credentials prompt an "invalid username or password" message.

        Home Page: Upon successful login, users are directed to a home page displaying company information, user details (username and roles), and a logout button.

        Role-Specific Links:
            Managers: Can access a "Leadership Meeting" page with a secret message tailored for managers.
            Admins: Can access an "IT Systems Meeting" page with a similar secret message exclusive to admins.
            Employees: Have restricted access and cannot see the links meant for managers or admins.

This project serves as an educational example of how to implement secure authentication and role-based access control in a Spring Boot application. Dive into the code to explore the configurations and functionalities that enable this robust security model.
