# A Sample BDD automation framework designed for KI

Technologies used -

Automation library: Selenium web driver library
Programming : Java 
Framework : Cucumber with Page Object Model
Build Tool : Maven

Github repo - https://github.com/hariprasadms/ki_bdd_automation_by_hari.git
Test run results - 
https://hariprasadms.github.io/ki_bddtest.html
https://hariprasadms.github.io/ki_bddtest_1.html
https://hariprasadms.github.io/ki_bddtest_2.html

Once checked-out the project. Run below command from project root location.

mvn clean test -Dcucumber.options="./src/test/resources/feature --tags @SmokeTest"

Note : Project is compiled and running on Java 11. It's been tested.

Thanks!

 
