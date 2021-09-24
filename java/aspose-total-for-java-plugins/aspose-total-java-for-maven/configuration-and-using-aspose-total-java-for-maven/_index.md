---
title: Configuration and Using Aspose.Total Java for Maven
type: docs
weight: 10
url: /java/configuration-and-using-aspose-total-java-for-maven/
---

## **Configuring Aspose.Total Java for Maven (Aspose Cloud Maven Reposiory) for a Maven Project**
Below are the steps will lead you to the successful configuration of Aspose Cloud Maven Repository for your Maven Projects.

**1.** First of all you need to specify Aspose Cloud Maven Repository configuration / location in your Maven pom.xml as below<repositories>

{{< highlight java >}}

 <repositories>

  <repository>

    <id>AsposeJavaAPI</id>

    <name>Aspose Java API</name>

    <url>http://repository.aspose.com/repo/</url>

  </repository>

</repositories>

{{< /highlight >}}

**2.** Define dependency of any Aspose.Java for Total API. For example, if you are Aspose.Words for Java API customer, you need to specify the following dependency to define in your pom.xml:

{{< highlight java >}}

 <dependency>

  <groupId>com.aspose</groupId>

  <artifactId>aspose-words</artifactId>

  <version>14.5.0</version>

</dependency>

{{< /highlight >}}

Above directive will let you create the Aspose.Words Java API maven dependency in your Maven project. Easy Job!

You can now use Aspose.Words Aspose API or can further create Aspose.Total for Java APIs dependencies in your Maven Project and use them for your project needs quite easily.

{{% alert color="primary" %}} 

Use the **<classifier> </classifier**> tag when defining dependencies, wherever applicable.

For example:

{{< highlight java >}}

 <dependencies>

   <dependency>

      <groupId>com.aspose</groupId>

      <artifactId>aspose-words</artifactId>

      <version>14.7.0</version>

      <classifier>jdk16</classifier>

   </dependency>

</dependencies>

{{< /highlight >}}

{{% /alert %}} 
### **Example Maven Projects for using Aspose.Total Java for Maven**
1. An example maven project with the above configuration included is being hosted on [GitHub Repository](http://goo.gl/hlFT1Z)
1. Another example project which is Spring web maven based project, demonstrate various Aspose.Total for Java APIs usage is also located on [GitHub Repository](https://github.com/asposemarketplace/Aspose_for_Spring.Java).
## **Configuring Aspose.Total Java for Maven Javadocs**
Aspose Cloud Maven Repository also supports the JavaDocs for all supported Aspose.Total for Java Product Line.

Major IDEs automatically downloads Aspose.Total for Java APIs Javadocs seemlessly and they are available right after in code windows once you define the APIs Maven dependency in pom.xml.

However there are certain options you may need to setup to configure your IDE to download Javadocs for Maven artifacts you use in your project.
### **Configure Eclipse IDE for JavaDocs**
You may need to configure your Eclipse ID to download javadoc jars automatically for you for the Aspose Java APIs Maven dependencies you defined in your maven projects.

This can be achieved by following steps mentioned below on Eclipse IDE:

1. Go into **Window** > **Preferences** > **Maven,** and
1. Check the **"Download Artifact JavaDoc"** option, as shown in below snapshot: 

![todo:image_alt_text](http://i.imgur.com/mRvzWGh.png)
### **Fetching Maven JavaDocs in Eclipse IDE**
Just hover the mouse cursor on class name or method name in Eclipse IDE source code editor to fetch the related javadocs.
### **Configure NetBeans IDE for JavaDocs**
For configuring NetBeans IDE to auto fetch javadoc jars for Aspose Java APIs Maven dependencies, you may need to follow the steps mentioned below on NetBeans IDE:

1. Go into **Tools > Options**, then
1. **Java > Dependencies,** and
1. Select the **Check Javadoc** to **"Every Project Open"** option under Dependency Download Strategy like shown in below snapshot: 

![todo:image_alt_text](http://i.imgur.com/KAJZwTj.png)
### **Fetching Maven JavaDocs in NetBeans IDE**
Hold the **CTRL** key and just hover mouse cursor on class name or method name in NetBeans IDE source code editor to fetch the related javadocs.
### **Configure IntelliJ IDEA for JavaDocs**
To configure IntelliJ IDEA to auto download javadoc jars for Aspose Java APIs maven dependencies, you will need to follow the below steps on IntelliJ IDEA:

1. Go into **File > Settings.. >** then,
1. **Maven > Importing**, and
1. Check the **"Documentation"** option under Automatically Download as shown in below snapshot:
### **Fetching Maven JavaDocs in IntelliJ IDEA**
After selecting method name or class name from source code press **CTRL+Q** to fetch the related javadocs, snapshot below showing javadocs.
## **Using**
### **Using Aspose.Total Java for Maven**
To use Aspose.Total Java for Maven (Aspose.Total for Java - Maven Artifacts) in the maven project. You first need to create / configure Aspose Maven based java project.

`       `For this,

- You may like to manually configure / create your Maven project as explained in [Configuring Aspose.Total Java for Maven](#configuring-asposetotal-java-for-maven-aspose-cloud-maven-reposiory-for-a-maven-project)
- Another thing you can do is to download the example Maven project that is hosted on [GitHib Repository](http://goo.gl/hlFT1Z) for this purpose.
- You can download and use any of Aspose Maven Plugins for Major IDEs to create Aspose Maven based project using the new project wizard feature in the plugin: 
  - [Aspose Maven for NetBeans](http://www.aspose.com/docs/display/totaljava/Aspose.Total+Project+Wizard+for+NetBeans+-+Maven)
  - [Aspose Maven for IntelliJ IDEA](http://www.aspose.com/docs/display/totaljava/Aspose.Total+Project+Wizard+for+IntelliJ+IDEA+-+Maven)
  - [Aspose Maven for Eclipse](http://www.aspose.com/docs/display/totaljava/Aspose.Total+Project+Wizard+for+Eclipse+-+Maven)
- You can use [Aspose Maven ArcheType (hosted on Aspose Cloud Maven Repository)](http://goo.gl/XPyp5n) for creating Aspose Maven based java projects.
  Detailed information on Aspose Maven ArcheType can be found on the following Aspose blogs: 
  - [Aspose Maven Dependencies Integrates with JetBrains IDE](https://blog.aspose.com/2014/10/03/aspose-maven-dependencies-integrates-with-jetbrains-ide/)
  - [Aspose Maven Dependencies Integrate with Eclipse IDE](https://blog.aspose.com/2015/01/07/aspose-maven-dependencies-integrates-with-eclipse-ide/)
  - [Aspose Maven Dependencies Integrate with NetBeans IDE](https://blog.aspose.com/2015/01/08/aspose-maven-dependencies-integrate-with-netbeans-ide/)

After you created / configured Aspose Maven project. You can untap the power of  "Aspose.Total for Java" APIs  in Maven based java project for your development needs.
### **Browsing Aspose.Total Java for Maven / Aspose Cloud Maven Repository**
The Aspose Cloud Maven Repository is located at the following URL.

<http://maven.aspose.com/artifactory/webapp/home.html>

You can browse the repository to find out the Artifacts it is currently serving, along with configuration required in pom.xml to use them in Maven based projects.
