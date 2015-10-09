Arquillian tests for JPA based on http://arquillian.org/guides/testing_java_persistence/

To run junit tests
==================
1. Using wildfly remote server (tested on WildFly 9.0.1)
	a) install and run wildfly appserver manually
	b) execute 
		mvn -P arquillian-wildfly-remote clean test

2. Using glassfish embedded server 
	a) execute
		mvn -P arquillian-glassfish-embedded clean test
