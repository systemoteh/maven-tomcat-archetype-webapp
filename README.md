# Maven Webapp Project with Tomcat
(template for IntelliJ IDEA Community Edition)

- Create new Maven project from archetype: maven-archetype-webapp
-------------------------------------------------------------------------------------------------------------
    groupId - ru.systemoteh
    artifactId - maven-tomcat-archetype-webapp
    version - 1.0
-------------------------------------------------------------------------------------------------------------
- In IDEA Toolbar -> Run -> Edit Configarations -> Add new configuration -> Maven
-------------------------------------------------------------------------------------------------------------
    Name - Tomcat 7
    Command line - tomcat7:run
-------------------------------------------------------------------------------------------------------------
- Before launch -> Add new -> Run Maven Goal:
-------------------------------------------------------------------------------------------------------------
    Command line - clean
-------------------------------------------------------------------------------------------------------------