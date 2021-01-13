Cuke-Up Your Tests
==================

## Download & Install:

- Java IDE: [IntelliJ community edition](https://www.jetbrains.com/idea/download/#section=windows) 
> You can use your own preferred IDE for Java (e.g. Eclipse). However the trainers know the settings and hotkeys for IntelliJ which are written in the [CheatSheet.docx](CheatSheet.docx), so the latter is preferred.
- Chrome Plugin: [CSS Selector Helper for Chrome](https://chrome.google.com/webstore/detail/css-selector-helper-for-c/gddgceinofapfodcekopkjjelkbjodin)
- [Git](https://git-scm.com)
- [Java jdk](http://www.oracle.com/technetwork/java/javase/downloads/index.html) (not the JRE)


## Setup

- Start up IntelliJ
- Choose 'Get from VCS' -> Git
- Fill in URL "https://github.com/dlammerse/cukeupyourtests.git"
- Press Clone
- When the following pop-up comes up select 'No': 

![versioncontrolcheckoutdone](https://user-content.gitlab-static.net/64c17cbbe30d2d474053ea05de843eddd2666d4a/68747470733a2f2f692e696d6775722e636f6d2f6b555842336e502e706e67)   


- In your IntelliJ main screen choose 'Open' and navigate to the folder to which you cloned the project in step 3. Select the pom.xml file and choose "Open as project".
- If it is your first IntelliJ project then in IntelliJ:
    - Select 'Open' project and browse to the test project folder you just created and open the folder
    - Open project structure (CTRL + Shift + Alt + S), navigate to the 'Project' tab, choose new in Project SDK section, select JDK and direct to your java/jdk folder
    - Open Settings (CTRL + ALT + S), navigate to 'Plugins' and install the plugins: `Gherkin` and `Cucumber for Java` (**Don't** install the `Substeps` plugin)
	- Open the Maven Projects Tool window (Navigation bar > `View` > `Tool Windows` > `Maven Projects`), this will open a view on the right side of the screen.
	- Double click under `cukeupyourtests` > `Lifecycle` the `compile` option. This will install the drivers of Chrome, Firefox and InternetExplorer. _If the drivers don't download you might be behind a proxy, visit [the plugin page](https://github.com/webdriverextensions/webdriverextensions-maven-plugin#using-a-proxy) for help_.

  

## Assignments
The assignments can be found in the file [Assignments.md](Assignments.md)

## Disclaimer
This is a workshop architecture and is only for that goal intended. Using this framework on a larger scale is not recommended.
