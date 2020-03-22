
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

    Goto Java SE download site @ http://www.oracle.com/technetwork/java/javase/downloads/index.html.
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
```markdown
    
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
 javac Hello.java
 java Hello
 ```
 
 Set the Current Drive to the drive where you saved your source file "Hello.java".
    If you use drive "c", skip this step.
    Else if you use drive "d", enter "d:" as follow: 

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/itwar-ir/java-introduction/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

