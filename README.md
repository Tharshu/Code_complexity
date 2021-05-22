# Code_complexity
Go to the folder "ACC" and build the java project using  > mvn clean install    Then run the jar file and start the backend service using the command 
>java -jar acc-0.0.1-SNAPSHOT.jar.
Go to the folder "ACCClient" and open the console and enter the below commands to start the react client.

> npm install

> npm run dev

Go to the folder "ACCScanner" build the java project using mvn clean install.
Run the Scaner using the following command in the command line console and give the paths of the files you want to analyse with a unique project key. 
NOTE: When running the ACCScanner the path should contain the given config folder.

java -DprojectKey={Unique Project Key} -DsourcePath={Path to the project source folder} -jar {ACCScanner jar file name}
eg:- java -DprojectKey=ACC -DsourcePath=E:\Development\algorithmic-complexity-calculator -jar core-1.0-SNAPSHOT-jar-with-dependencies.jar

Go to the url http://localhost:1234/home in your browser.
