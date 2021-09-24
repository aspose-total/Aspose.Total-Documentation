---
title: Aspose.Total Java for Maven
type: docs
weight: 40
url: /java/aspose-total-java-for-maven/
---

## **Introduction**
### **Introduction to Maven**
Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

The following are the key features of Maven in a nutshell:

- Simple project setup that follows best practices - get a new project or module started in seconds
- Consistent usage across all projects means no ramp up time for new developers coming onto a project
- Superior dependency management including automatic updating, dependency closures (also known as transitive dependencies)
- A large and growing repository of libraries and metadata to use out of the box, and arrangements in place with the largest Open Source projects for real-time availability of their latest releases
- Dependency management: Maven encourages the use of a central repository of JARs and other dependencies. Maven comes with a mechanism that your project's clients can use to download any JARs required for building your project from a central JAR repository / Third party repository like [Aspose Cloud Maven Repository](http://maven.aspose.com/artifactory/webapp/home.html) (provides Aspose.Total for Java APIs Maven Dependencies). This allows users of Maven to reuse JARs across projects and encourages communication between projects.
### **Introduction to Maven Repositories**
A repository in Maven is used to hold build artifacts and dependencies of varying types.

There are strictly only two types of repositories: **local** and **remote**. The local repository refers to a copy on your own installation that is a cache of the remote downloads, and also contains the temporary build artifacts that you have not yet released.

**Remote repositories** refer to any other type of repository, accessed by a variety of protocols such as file:// and http://.

These repositories might be a truly remote repository set up by a third party to provide their artifacts for downloading (for example, [repo.maven.apache.org](http://repo.maven.apache.org/maven2/) / [uk.maven.org](https://repo1.maven.org/maven2/uk/) house Maven's central repository and [maven.aspose.com](http://maven.aspose.com/artifactory/webapp/home.html) for holding **Aspose.Total for Java APIs artifacts**). Other "remote" repositories may be internal repositories set up on a file or HTTP server within your company, used to share private artifacts between development teams and for releases.

The local and remote repositories are structured the same way so that scripts can easily be run on either side, or they can be synced for offline used. In general use, the layout of the repositories is completely transparent to the Maven user, however.
### **Aspose.Total for Java**
[Aspose.Total for Java](http://www.aspose.com/java/total-component.aspx) is a compilation of every Java API offered by Aspose. Using Aspose.Total for Java developers can create a wide range of applications, each leveraging the combined power of all Aspose Java components that are included as part of the Aspose.Total for Java suite.
## **Aspose.Total Java for Maven**
**Aspose.Total Java for Maven** are Aspose's Maven artifacts (for [Aspose.Total for Java](http://www.aspose.com/java/total-component.aspx)) provided by Aspose's maintained private maven repository, which is also known as [Aspose Cloud Maven Repository](http://maven.aspose.com/artifactory/webapp/home.html).

Aspose Cloud Maven Repository was launched on August 12, 2014 to provide maven artifacts for [Aspose.Total for Java](http://www.aspose.com/java/total-component.aspx) since then it is housing Aspose artifacts none-stop.

Artifacts for new APIs releases become available immediately,  facilitating the APIs users to easily use well up to date APIs in Maven based java projects. (can be used in Gradle and Ivy projects also)

And as a feature to Maven project model, there is no manual downloadings are needed for Aspose.Total for Java APIs which is taken care by the Maven project dependency management. Developer will just use the dependency directive in pom.xml for creating any [Aspose.Total for Java](http://www.aspose.com/java/total-component.aspx) API dependency.

## **System Requirements and Supported Platforms**
### **System Requirements**
- **System Memory:** 2 GB or more (Recommended)
- **OS:** Any operating system that supports the Java VM (Virtual Machine)
- **Internet Connection:** 2 MB or faster (Recommended)
### **Supported Platforms**
- Maven
- Gradle
- Ivy
- Major Java IDEs
## **Supported Product Line**
The following [Aspose.Total for Java APIs](http://www.aspose.com/java/total-component.aspx) artifacts (along with Javadocs) are supported by Aspose Cloud Maven Repository.

|**Product**|**Maven Dependency**|
| :- | :- |
|**Aspose.Cells for Java**| |
|<p>![todo:image_alt_text](http://www.aspose.com/App_Themes/V2/images/productLogos/Java/aspose_cells-for-java.jpg)</p><p></p>|<p>{{< highlight java >}}</p><p> <dependency></p><p>  <groupId>com.aspose</groupId></p><p>  <artifactId>aspose-cells</artifactId></p><p>  <version>${aspose-cells.version}</version></p><p></dependency></p><p></p><p>{{< /highlight >}}</p>|
|**Aspose.Words for Java**| |
|![todo:image_alt_text](http://www.aspose.com/App_Themes/V2/images/productLogos/Java/aspose_words-for-java.jpg)|<p>{{< highlight java >}}</p><p> <dependency></p><p>  <groupId>com.aspose</groupId></p><p>  <artifactId>aspose-words</artifactId></p><p>  <version>${aspose-words.version}</version></p><p></dependency> </p><p>{{< /highlight >}}</p>|
|**Aspose.Pdf for Java**| |
|![todo:image_alt_text](http://www.aspose.com/App_Themes/V2/images/productLogos/Java/aspose_pdf-for-java.jpg)|<p>{{< highlight java >}}</p><p> <dependency></p><p>  <groupId>com.aspose</groupId></p><p>  <artifactId>aspose-pdf</artifactId></p><p>  <version>${aspose-pdf.version}</version></p><p></dependency> </p><p>{{< /highlight >}}</p>|
|**Aspose.Slides for Java**| |
|![todo:image_alt_text](http://www.aspose.com/App_Themes/V2/images/productLogos/Java/aspose_slides-for-java.jpg)|<p>{{< highlight java >}}</p><p> <dependency></p><p>  <groupId>com.aspose</groupId></p><p>  <artifactId>aspose-slides</artifactId></p><p>  <version>${aspose-slides.version}</version></p><p></dependency> </p><p>{{< /highlight >}}</p>|
|**Aspose.BarCode for Java**| |
|![todo:image_alt_text](http://www.aspose.com/App_Themes/V2/images/productLogos/Java/aspose_barcode-for-java.jpg)|<p>{{< highlight java >}}</p><p> <dependency></p><p>  <groupId>com.aspose</groupId></p><p>  <artifactId>aspose-barcode</artifactId></p><p>  <version>${aspose-barcode.version}</version></p><p></dependency> </p><p>{{< /highlight >}}</p>|
|**Aspose.Tasks for Java**| |
|![todo:image_alt_text](http://www.aspose.com/App_Themes/V2/images/productLogos/Java/aspose-Tasks-for-Java-web.png)|<p>{{< highlight java >}}</p><p> <dependency></p><p>  <groupId>com.aspose</groupId></p><p>  <artifactId>aspose-tasks</artifactId></p><p>  <version>${aspose-tasks.version}</version></p><p></dependency> </p><p>{{< /highlight >}}</p>|
|**Aspose.Email for Java**| |
|![todo:image_alt_text](http://www.aspose.com/App_Themes/V2/images/productLogos/Java/aspose_email-for-java.jpg)|<p>{{< highlight java >}}</p><p> <dependency></p><p>  <groupId>com.aspose</groupId></p><p>  <artifactId>aspose-email</artifactId></p><p>  <version>${aspose-email.version}</version></p><p></dependency> </p><p>{{< /highlight >}}</p>|
|**Aspose.Diagram for Java**| |
|![todo:image_alt_text](http://www.aspose.com/App_Themes/V2/images/productLogos/Java/aspose_diagram-for-java.jpg)|<p>{{< highlight java >}}</p><p> <dependency></p><p>  <groupId>com.aspose</groupId></p><p>  <artifactId>aspose-diagram</artifactId></p><p>  <version>${aspose-diagram.version}</version></p><p></dependency> </p><p>{{< /highlight >}}</p>|
|**Aspose.OCR for Java**| |
|![todo:image_alt_text](http://www.aspose.com/App_Themes/V2/images/productLogos/Java/aspose_ocr-for-java.jpg)|<p>{{< highlight java >}}</p><p> <dependency></p><p>  <groupId>com.aspose</groupId></p><p>  <artifactId>aspose-ocr</artifactId></p><p>  <version>${aspose-ocr.version}</version></p><p></dependency> </p><p>{{< /highlight >}}</p>|
|**Aspose.Imaging for Java**| |
|![todo:image_alt_text](http://www.aspose.com/App_Themes/V2/images/productLogos/Java/aspose_imaging-for-java.jpg)|<p>{{< highlight java >}}</p><p> <dependency></p><p>  <groupId>com.aspose</groupId></p><p>  <artifactId>aspose-imaging</artifactId></p><p>  <version>${aspose-imaging.version}</version></p><p></dependency> </p><p>{{< /highlight >}}</p>|
## **Configuration**
[Configuring Aspose.Total Java for Maven](http://www.aspose.com/docs/display/totaljava/Configuration+and+Using+Aspose.Total+Java+for+Maven)
## **Using**
[Using Aspose.Total Java for Maven](http://www.aspose.com/docs/display/totaljava/Configuration+and+Using+Aspose.Total+Java+for+Maven#ConfigurationandUsingAspose.TotalJavaforMaven-Using)
## **Support and Consulting Services**
- [Consulting and Support Services](http://www.aspose.com/corporate/services/default.aspx)
- [Free Support](http://www.aspose.com/corporate/services/free-support-policies.aspx)
