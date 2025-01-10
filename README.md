# TWEB_Project

## Instructions for running the project  

### In IntelliJ:  
#### SDK
Navigate to File/Project Structure/Project/    
- Set the SDK to SDK22 (Oracle OpenJDK 22.0.1)  
#### Gradle
1. **File > Project Structure > Modules**.  
**Add a Gradle module:**  
  * Click on the ‘+’ button in the top left-hand corner.  
  * Select **Import Module**.  
  * Navigate to the file : solution/SpringBootServer/build.gradle  
2. View > Tool Windows > Gradle and click on **Reload All Gradle Projects**.  

### Install Node.js Dependencies
In the terminal, go to the solution/MongoDBServer folder and enter the commands:  
- npm install  
- npm uninstall mongoose  
- npm install mongoose@latest

### Run the Servers
At the top, to the left of the ‘Run’ button, choose CurrentFile then run the files:  
- solution/MainServer/bin/www.js  
- solution/MongoDBServer/bin/www.js  
- solution/SpringBootServer/src/main/java/it/unito/iumtweb/springboot/FirstExampleApplication.java

Finally, access the site in Google Chrome at the URL: http://localhost:3000/  
