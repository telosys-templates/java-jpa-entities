# JPA entities with JUnit test cases

This bundle generates the following Java files:

 - in "**project-root**"  
   - **pom_jpa.xml** : a "pom.xml" file for JPA (designed to be renamed to "pom.xml")
   
 - in "**src/main/java/{package}/entities**"  
   - **{entity-name}.java** : JPA entity (with JPA annotations)  
   - **{entity-name}Id.java** : JPA composite primary key (if any)  
   
 - in "**src/main/resources/META-INF**"  
   - **persistence.xml** : a JPA configuration file example
   
 - in "**src/test/java/{package}/entities**"  
   - **{entity-name}JpaTest.java** : JPA JUnit test case

 - in "**src/test/java/jpa/data**"  
   - **{entity-name}Data.java** : JPA data initialization 

 - in "**src/test/java/jpa/tools**"  
   - **DatabaseInit.java** : Database initialization before unit tests
   - **JpaTest.java** : abstract class for JPA JUnit test
   
 - in "**src/test/resources/META-INF**"  
   - **persistence.xml** : the JPA configuration file for test cases with H2 database

    
 
   