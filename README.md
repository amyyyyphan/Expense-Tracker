**Project Description**

Expense is an application that helps people keep track of their expenses. It is a 3-tier architecture application that uses React as its presentation tier, Java and Spring boot for its application tier, and Amazon RDS as its data tier.


**Requirements to run application on localhost**
  - Java JDK
  - Maven
  - NPM (https://www.npmjs.com/get-npm)
  
Optional:
  - MySql Client to view database


**Steps to run application on localhost**
  1. Clone repository from github
  2. Start Backend:\
        Run DemoApplication.java
  3. Start Frontend:\
        Open terminal\
        Navigate to frontend\app directory\
        Run “npm install”\
        Run “npm start”
        
The application should open on a browser.





**To run Backend on Docker on localhost**
  1. Open Terminal
  2. Navigate to the main directory containing the Dockerfile
  3. Run “docker build -t expense-tracker .” (this will take some time)
  4. Run “docker run -p 8080:8080 expense-tracker”
  5. Then start Frontend on a new terminal
