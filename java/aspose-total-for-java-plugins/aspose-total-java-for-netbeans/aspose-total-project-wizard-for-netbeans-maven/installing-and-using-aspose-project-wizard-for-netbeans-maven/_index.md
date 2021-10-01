---
title: Installing and Using Aspose Project Wizard for NetBeans - Maven
type: docs
weight: 10
url: /java/installing-and-using-aspose-project-wizard-for-netbeans-maven/
---

## **Installing**
### **Installing Aspose.Total Java for NetBeans (Maven) plugin**
The **Aspose Maven Project Wizard** plugin can be directly downloaded from [NetBeans plugin portal website](http://plugins.netbeans.org/plugin/57279), and then can be installed in NetBeans IDE (using **Tools** > **Plugins** > **Downloaded** > **Add plugin**).

But as this plugin is also available on the NetBeans Plugin Portal Update Center. For more convenient installation of this plugin

1. Use ‘**Tools** > **Plugins**‘ action from the NetBeans IDE main menu
1. Click ‘**Available** **Plugins**‘ Tab and type ‘**Aspose**‘ in search box. As shown below: 

![todo:image_alt_text](http://i.imgur.com/iBS2q3f.png)

1. Select ‘**Aspose Maven Project Wizard**‘ plugin and click **Install**
1. Accept license agreement – MIT License for this plugin and Click **Install.**
1. This will trigger installation of the plugin and you may be asked to ‘**Continue**‘ and also ‘**Finish**‘ the installation after which you can start using the plugin in NetBeans IDE without any restarts. 

The Plugin will introduce a new project type – 

![todo:image_alt_text](https://camo.githubusercontent.com/b360643e823e0236ed55e2ae5a8de8e9c970ee92/687474703a2f2f692e696d6775722e636f6d2f70537a58656f772e706e67)

**Aspose Maven Project** – inside ‘**Maven’** category on New Project (Wizards) dialog in NetBeans, which will allow you to create Aspose Maven based Java projects inside the IDE. 

![todo:image_alt_text](http://i.imgur.com/Y7Kbw78.png)
## **Using**
### **Creating Aspose's Maven Project using plugin's - Aspose Maven Project Wizard**
The Wizard allows developers to create Maven based project for using Aspose.Total for Java API inside NetBeans IDE. The desired [Aspose.Total for Java APIs](http://www.aspose.com/java/total-component.aspx) can be selected on wizards steps to include the maven dependencies in your creating maven based project

1. Select **New Project** from NetBeans **File** menu
1. Under **Maven** category of Wizards, select ‘**Aspose Maven Project’**
1. Click **Next**. 
1. Provide a **Project Name** and **Location** just like when creating any Java application.
1. Also provide **Group Id, Artifact Id,** **Version** and **Package** (optional field) for your maven project and click **Next**. 
1. Select **Aspose API(s)** from the list. 

![todo:image_alt_text](http://i.imgur.com/v74ld9R.png)

1. Click **Finish**.
   This will retrieve the selected Aspose APIs latest maven dependencies references from [Aspose Cloud Maven Repository](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo). 

Congratulations! you have successfully created Aspose maven based project for your selected Aspose APIs using Aspose Maven Project wizard inside the NetBeans IDE.

One cool thing, every time you create Maven project using the wizard will create maven project containing latest maven dependencies for the selected Aspose APIs along with the **Aspose Cloud Maven Repository** configuration in the pom.xml. See the snapshot below:

![todo:image_alt_text](http://i.imgur.com/ji1NDF0.png)


Thanks to [Aspose Maven Project wizard](http://plugins.netbeans.org/plugin/57279) Plugin !

Now the created Aspose maven based project is ready to be enhanced as per your project’s development needs inside the NetBeans IDE !
