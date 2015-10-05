Arquillian tests for EJB+CDI based on http://arquillian.org/guides/getting_started_rinse_and_repeat/

To run junit tests
==================
1. Using wildfly remote server (tested as WildFly 9.0.1)
	mvn -P arquillian-wildfly-remote clean test

2. Using glassfish remote server 
	mvn -P arquillian-glassfish-remote clean test
