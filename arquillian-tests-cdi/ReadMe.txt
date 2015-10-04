Date: 04 Oct, 2015 
This tutorial based on http://arquillian.org/guides/getting_started/
but uses update versions of the dependencies.

To run from command line
========================
a) using arquillian-weld-ee-embedded profile
	mvn -P arquillian-weld-ee-embedded clean test
b) using arquillian-glassfish-embedded
	mvn -P arquillian-glassfish-embedded clean test
c) deploy to remote wildfly appserver a
	1. start wildfly server manually (no arquillian.xml file used in this test sample)
	2. mvn -P arquillian-wildfly-remote clean test
	