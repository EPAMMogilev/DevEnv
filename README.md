# Development environment set up

---
## Feel free to change instructions and rules here. This is only draft version.

# IDE

Set up your IDE as the following:
* use spaces for tabs
* set up auto code formatting (you can skip this after reading and following [this](https://google-styleguide.googlecode.com/svn/trunk/javaguide.html) or [this](http://www.oracle.com/technetwork/java/codeconvtoc-136057.html))

# Code Quality

## Set up code quality checking tools:

* [PMD](http://pmd.sourceforge.net/)
  * Usually we use a maven [plugin](http://maven.apache.org/plugins/maven-pmd-plugin/)
  * Set up plugin to use pmd rules file from this repository

* [Checkstyle](http://checkstyle.sourceforge.net/)
  * Maven [plugin](http://maven.apache.org/plugins/maven-checkstyle-plugin/)
  * Set up plugin to use rules file from this repository

* [FindBugs](http://findbugs.sourceforge.net/)
  * Maven [plugin](http://mojo.codehaus.org/findbugs-maven-plugin/)
  * Set up plugin to use rules file from this repository

## Before pushing to remote repository:

* Make sure that your code passes all pmd, findbugs and checkstyle checks
* Code is covered with unit tests
* Code review is passed



![watching you](http://www.thetruthaboutcars.com/wp-content/uploads/2013/09/watching-you-uncle-sam-poster-Big-Brother-1984-Orwellian.jpg)


