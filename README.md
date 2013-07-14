SpringSecurityLogoutExample
===========================

Spring Security provides Logout Handling Service for logging out by navigating to a particular URL (by default /j_spring_security_logout). <a href="http://static.springsource.org/spring-security/site/docs/3.1.x/apidocs/org/springframework/security/web/authentication/logout/LogoutFilter.html" target="_blank">LogoutFilter</a> starts processing when a request comes for <strong>/j_spring_security_logout</strong> url and delegates to <strong>LogoutHandler</strong>(s) to perform the actual logout functionality like clearing security context, invalidating session, etc. Based on logout configuration, a redirect will be performed to the URL <strong>logout-success-url</strong> after logout.

<a href="http://www.srccodes.com/p/article/32/spring-security-logout-example" target="_blank" >Continue Reading</a>
