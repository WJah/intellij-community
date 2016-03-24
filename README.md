# IntelliJ IDEA Community Edition
### Building and Running from the IDE
To develop IntelliJ IDEA, you can use either IntelliJ IDEA Community Edition or IntelliJ IDEA Ultimate not older than 15.0. To build and run the code:
* Run **getPlugins.sh** / **getPlugins.bat** from the project root directory to check out additional modules.
* If this git repository is not on 'master' branch you need to checkout the same branches/tags in android and android/tools-base git repositories.
* Open the project.
* If an error notification about a missing required plugin (e.g. Kotlin) is shown enable or install that plugin.
* Configure a JSDK named "**IDEA jdk**" (case sensitive), pointing to an installation of JDK 1.6.
* Unless you're running on a Mac with an Apple JDK, add <JDK_HOME>/lib/tools.jar to the set of "**IDEA jdk**" jars.
* Configure a JSDK named "**1.8**", pointing to an installation of JDK 1.8.
* Add <JDK_18_HOME>/lib/tools.jar to the set of "**1.8**" jars.
* Use Build | Make Project to build the code.
* To run the code, use the provided shared run configuration "**IDEA**".

You can find other useful information at [http://www.jetbrains.org](http://www.jetbrains.org). [Contribute section](http://www.jetbrains.org/display/IJOS/Contribute) of that site describes how you can contribute to IntelliJ IDEA.

-------------modified by Jiahe Wang as below--------------
* all work is done under branch 145
* modify getPlugin.sh to get android plugins from git@github.com:WJah/android.git and git@github.com:WJah/adt-tool-base.git
* modify intellij idea DeleteHandler.java to update R.java after delete layout xml file
* other work is done under https://github.com/WJah/android and https://github.com/WJah/adt-tools-base. Read their README.md For detail 
