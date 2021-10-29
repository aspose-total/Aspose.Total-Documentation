---
title: Downloading, Installing and Using Aspose Java for Spring
type: docs
weight: 10
url: /java/downloading-installing-and-using-aspose-java-for-spring/
---

## **Downloading**
Aspose for Spring Java (Extension of PetClinic Sample Web Application) is can be downloaded from any of the social coding websites listed below.

- [GitHub](https://github.com/asposemarketplace/Aspose_for_Spring.Java)
- [SourceForge](https://sourceforge.net/projects/asposeforspringjava/)
- [Bitbucket](https://bitbucket.org/asposemarketplace/aspose-for-spring.java/src/master/)

## **Configuring and Installing Aspose Java for Spring**
Below simple steps will smoothly lead to successful configuration of Spring Java PetClinic Sample Web Application for Aspose API source code in IntelliJ IDE / Eclipse IDE
## **Prerequisites:**
- ### **Working with PetClinic in JetBrains**
The following items should be installed in your system:# Maven 3 (<https://maven.apache.org/download.cgi>)

1. git command line tool (<https://docs.github.com/en/get-started/quickstart/set-up-git>)
1. IntelliJ IDEA CE / UE* h3. Working with PetClinic in Eclipse/STS
   The following items should be installed in your system:# Maven 3 (<https://maven.apache.org/download.cgi>)
1. git command line tool (<https://docs.github.com/en/get-started/quickstart/set-up-git>)
1. Eclipse with the m2e plugin (m2e is installed by default when using the STS (<https://spring.io/tools>) distribution of Eclipse) {{% alert color="primary" %}} 

When m2e is available, there is an m2 icon in Help -> About dialog
If m2e is not there, just follow the install process here: <http://eclipse.org/m2e/download/>

{{% /alert %}}
- ### **Running PetClinic locally**
1. git clone <https://github.com/asposemarketplace/Aspose_for_Spring.Java.git>
1. mvn tomcat7:run
1. You can then access petclinic here: `http://localhost:9966/petclinic/` {{% alert color="primary" %}} 

In case of any PermGen related JVM error, adjust PermGen memory space by setting the appropriate values to MAVEN_OPTS environment variable. 
For Example: 
export MAVEN_OPTS="-Xmx512m -XX:MaxPermSize=128m" 
-OR- 
(on Windows) 
set MAVEN_OPTS=-Xmx512m -XX:MaxPermSize=128m

{{% /alert %}}
## **Steps:**
1. In the command line
   "git clone <https://github.com/asposemarketplace/Aspose_for_Spring.Java.git>" 
1. **Inside Eclipse** 
   File -> Import -> Maven -> Existing Maven project
   **Inside IntelliJ IDEA** 
   File--> Open -> select spring-petclinic Project
1. Open Browser and Navigate to <http://localhost:9966/peclinic/>



![todo:image_alt_text](https://i.imgur.com/iYcyGwP.png)
## **Tutorials:**
- [Aspose.Words API Demonstration for Spring Java](/total/java/aspose-words-api-demonstration-for-spring-java/)
- [Aspose.Cells API Demonstration for Spring Java](/total/java/aspose-cells-api-demonstration-for-spring-java/)
- [Aspose.Pdf API Demonstration for Spring Java](/total/java/aspose-pdf-api-demonstration-for-spring-java/)
- [Aspose.BarCode API Demonstration for Spring Java](/total/java/aspose-barcode-api-demonstration-for-spring-java/)
- [Aspose.Email API Demonstration for Spring Java](/total/java/aspose-email-api-demonstration-for-spring-java/)
