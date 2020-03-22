
## Welcome to Java Introduction Course  Pages

This course is designed to familiarize you with the Java programming language. This site provides all the requirements for course training including :
 - slides
 - source codes 
 - required resources


The different sections of each chapter describe the requirements for code execution.

# Requirment

The hardware and software requirements to learn this course include:
 - A computer with any kind of operating system
 - Install JDK to fit the operating system
 - Installing an IDE like Netbeans.

## How To Install JDK on Windows

1. Un-Install Older Version(s) of JDK/JRE

I recommend that you install only the latest JDK. Although you can install multiple versions of JDK/JRE concurrently, it is messy.

If you have previously installed older version(s) of JDK/JRE, un-install ALL of them. Goto "Control Panel" ⇒ (optional) "Programs" ⇒ "Programs and Features" ⇒ Un-install ALL programs begin with "Java", such as "Java SE Development Kit ...", "Java SE Runtime ...", "Java X Update ...", and etc.

 1. Download JDK

    Goto [Java SE download](http://www.oracle.com/technetwork/java/javase/downloads/index.html).
    Under "Java Platform, Standard Edition" ⇒ "Java SE 8.0.{x}", where {x} denotes a fast running security-update number ⇒ Click the "Oracle JDK Download" button.
    Under "Java SE Development Kit 8.0.{x}" ⇒ Check "Accept License Agreement".
    Choose the JDK for your operating system, i.e., "Windows". Download the "exe" installer (e.g., "jdk-8.0.{x}_windows-x64_bin.exe").

2. Install JDK

Run the downloaded installer (e.g., "jdk-8.0.{x}_windows-x64_bin.exe"), which installs both the JDK and JRE.

By default, JDK is installed in directory "C:\Program Files\Java\jdk-8.0.{x}", where {x} denotes the update number. Accept the defaults and follow the screen instructions to install JDK.

Use your "File Explorer", navigate to "C:\Program Files\Java" to inspect the sub-directories. Take note of your JDK installed directory jdk-8.0.{x}, in particular, the update number {x}, which you will need in the next step.

I shall refer to the JDK installed directory as <JAVA_HOME>, hereafter, in this article.

3. Verify the JDK Installation
 Launch a CMD via one of the following mean
 - Use Windows Key + R 
 - type cmd in run windows
    
```in console type
java -version 
java version "1.8.0_241"
Java(TM) SE Runtime Environment (build 1.8.[x])
Java HotSpot(TM) 64-Bit Server VM (build [Y], mixed mode)
```
4. Write a Hello-World Java Program
Create a directory to keep your works, e.g., "d:\myProject" or "c:\myProject". 
Launch a programming text editor (such as TextPad, NotePad++, Sublime Text, Atom). Begin with a new file and enter the following source code. Save the file as "Hello.java", under your work directory (e.g., d:\myProject). 
```type in Hello.java file
/*
 * First Java program to say Hello
 */
public class Hello {   // Save as "Hello.java" under "d:\myProject"
   public static void main(String[] args) {
      System.out.println("Hello, world!");
   }
}
```
5. Compile and Run the Hello-World Java Program
To compile the source code "Hello.java":

   - Use Windows Key + R 
   - type cmd in run windows
 ```in console type
 cd d:
 d:
 cd myProject
 ````
 Invoke the JDK compiler "javac" to compile the source code "Hello.java". 
 ```compile Hello.java
 javac Hello.java
 // If error message appears, correct your source code and re-compile
 ```
 The compilation is successful if the command prompt returns. Otherwise, error messages would be shown. Correct the errors in your source file and re-compile. Check "Common JDK Installation Errors", if you encounter problem compiling your program.
The output of the compilation is a Java class called "Hello.class". Issue a dir (List Directory) command again to check for the output. 
 To run the program, invoke the Java Runtime "java"
 ```Dir out put
 dir
 ......
xx-xxx-xx  xx:xx PM               416 Hello.class
xx-xxx-xx  xx:xx PM               277 Hello.java
......
 ```
To run the program, invoke the Java Runtime "java":
 ```run Hello
 java Hello
 Hello, world!
 ```
 ### for more information [installation-jdk-microsoft-windows](https://docs.oracle.com/en/java/javase/13/install/installation-jdk-microsoft-windows-platforms.html#GUID-371F38CC-248F-49EC-BB9C-C37FC89E52A0).
 
 ## How To Install Netbeans on Windows
Goto [NetBeans11.1 IDE download](https://www.apache.org/dyn/closer.cgi/netbeans/netbeans/11.1/Apache-NetBeans-11.1-bin-windows-x64.exe) .
After donload finished install netbeans11 if have a paroblem [Watch install NetBeans IDE](https://youtu.be/yX-qG2Ooqzk)




