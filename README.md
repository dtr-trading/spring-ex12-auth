spring-ex12-auth
======================

This example builds on spring-ex11-auth, where we restricted access to the "strategy" pages to users with the role "ROLE_ADMIN".  We also updated the LinkController to direct users to one of the three role specific home pages.  In this example, we will customize the access denied (403) page.  Besides creating the html error page, we will create an exception handler and new controller, plus update two configuration files.  This example uses Spring 4.0.2 and Spring Security 3.2.3, and uses java configuration files rather than XML.

This example has been validated with the following environment on MS Windows 7:

1. Eclipse Kepler
   1.1 Spring Tool Suite (STS) 3.4.0.RELEASE - for Kepler
2. Java SDK 1.7.0_51 (separate install)
3. Tomcat 7.0.50 (separate install)
4. Maven 3.0.5 (separate install)
5. MySQL 5.5.29
