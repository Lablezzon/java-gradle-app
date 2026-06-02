#  CodeAlpha Java Gradle CI/CD Project

## 📌 Overview
This project is a simple Java application built using Gradle and integrated with a CI/CD pipeline using GitHub Actions. It demonstrates core DevOps practices such as build automation, dependency management, and continuous integration.


## ⚙️ Features
- Java 21 application
- Gradle build automation
- Dependency management (Maven Central)
- Unit testing support (JUnit Jupiter)
- CI/CD pipeline using GitHub Actions
- Automated build on every push to `main`


## 🧱 Project Structure

java-gradle-app/
├── app/
│ └── src/main/java/org/example/App.java
├── build.gradle
├── settings.gradle
├── gradlew
├── gradle/
└── .github/workflows/gradle.yml


# 🚀 How to Run Locally

# Run the application
``bash
./gradlew :app:run

Build the project
./gradlew clean :app:build

Run tests
./gradlew test

🔄 CI/CD Pipeline (GitHub Actions)

This project uses GitHub Actions for continuous integration.

Every push to the main branch triggers:

Code checkout
Java setup (Temurin 21)
Gradle build
Automated testing

Workflow file location:

.github/workflows/gradle.yml

🛠 Tech Stack

Java 21

Gradle 9.5.1

JUnit 5

GitHub Actions

Ubuntu (CI environment)

📦 Key Learning Outcomes

Setting up a Java project with Gradle

Managing dependencies using build.gradle

Running and testing Java applications

Automating builds using CI/CD pipelines

Understanding DevOps workflows in real projects

👨‍💻 Author

Blessing Taiwo

https://github.com/Lablezzon

CodeAlpha Internship Project
