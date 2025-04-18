# java-maven
This project demonstrates how to build a basic Java application using Maven and automate the process using Jenkins Continuous Integration (CI).

🔧 Tools Used
1. Java JDK (version 21 used)
2. Apache Maven
3. Jenkins (running locally via Docker)
4. Git & GitHub for version control

📁 Project Overview
A simple "Hello World" Java application with a pom.xml file configured for Maven build. The project is set up in GitHub and integrated with Jenkins for automated building.

✅ Task Steps
# Create Java Project
-> Created a basic Java application and pom.xml file.

# Push Code to GitHub
-> Uploaded the project to GitHub repository: java-maven.

# Set Up Jenkins
-> Installed and ran Jenkins locally using Docker.
-> Configured Java and Maven in Jenkins under Global Tool Configuration.
-> Create Jenkins Freestyle Job.
-> Configured a new freestyle project in Jenkins.
-> Connected to the GitHub repository using HTTPS URL.
-> Updated branch name to main (not master).
-> Added a build step to invoke Maven with clean package.
-> Build & Verify.
-> Triggered a manual build.
-> Verified build was successful with BUILD SUCCESS message in Jenkins Console Output.

---
