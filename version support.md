# Apache Tomcat
## version support
> [!CAUTION]
> To run a Tomcat successfully, please notice the version support of related tools.
>
> If related tools does NOT satisfy the version support. You will see there are lots of error when adding project to Tomcat Server. Discussed in next section.

The first column indicates the release date of Tomcat Server.

The second column indicates the release version of Tomcat Server.

The third column indicates **_minimum version requirement_** of Java.

The fourth column indicates **_(exact) version requirement_** of **_javax.servlet and its related packages_**. **Neither** older **nor** newer version of **_javax.servlet and its related packages_** is not supported.

The fifth column indicates **_(exact) version requirement_** of **_JSP/EL_**. **Neither** older **nor** newer version of **_JSP/EL_** is not supported.

Image source from William's ppt on TibeMe course.

<img width="729" alt="Screenshot 2024-10-28 210023" src="https://github.com/user-attachments/assets/088f5009-2ab5-4d5b-ae5e-646815798d02">

For example, 

Tomcat Server v9.0 is released at Jan, 2018. 

To use Tomcat Server v9.0, Java version 8 or later is required.  

Version 4.0 of **_javax.servlet and its related packages_** (not later) is required. Later version of 4.0 is not supported.

Version 2.4 of **_JSP_** (not later) is required. Later version of 2.4 is not supported.

Version 3.1 of **_EL_** (not later) is required. Later version of 3.1 is not supported.

## issues when version incompatible
The following issues (including but not limited to) may occur if the version is incompatible between Tomcat Server and its related tools.

> [!WARNING]
> The detailed message of issue may be different in different IDE. But they points to same problem. I'll discuss the detailed message of issues in Eclipse IDE.

1. `Project facet Java version 21 is not supported.` when try to add a project to Tomcat Server in Eclipse.

<img width="430" alt="image" src="https://github.com/user-attachments/assets/cdcb675e-7eaa-4637-afd7-327322b51fe8">







