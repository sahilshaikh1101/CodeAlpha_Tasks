# ☕ CodeAlpha Java Application using Gradle

## 📖 Project Description

This project demonstrates the development, build automation, and execution of a Java application using Gradle on RHEL 9 Linux as part of the CodeAlpha DevOps Internship.

The objective of this project is to understand build automation, dependency management, project structure, and the Gradle build lifecycle in Java application development.

---

## 🎯 Objectives

- Learn Gradle build automation
- Understand Java project structure
- Automate compilation and execution
- Manage dependencies efficiently
- Understand build lifecycle concepts
- Gain hands-on experience with DevOps development workflows

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Java 17 | Application Development |
| Gradle | Build Automation Tool |
| RHEL 9 | Operating System |
| Git | Version Control |
| GitHub | Repository Hosting |

---

## 📂 Project Structure

```text
CodeAlpha_Gradle_Project/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   └── test/
│
├── gradle/
├── gradlew
├── gradlew.bat
├── settings.gradle
├── build.gradle
└── README.md
```

---

## ⚙️ Application Code

```java
package org.example;

public class App {
    public static void main(String[] args) {
        System.out.println("CodeAlpha Gradle Project Running Successfully");
        System.out.println("Created by Sahil Shaikh");
    }
}
```

---

## 🚀 Project Implementation

### Step 1: Install Java

```bash
java -version
```

### Step 2: Install Gradle

```bash
gradle -v
```

### Step 3: Create Gradle Project

```bash
gradle init
```

### Step 4: Modify Application Code

Updated the default Java application with custom output.

### Step 5: Build Project

```bash
gradle build
```

### Step 6: Run Application

```bash
gradle run
```

---

## 🔧 Gradle Commands Used

### Initialize Project

```bash
gradle init
```

### Build Project

```bash
gradle build
```

### Run Application

```bash
gradle run
```

### Clean Build Files

```bash
gradle clean
```

### Rebuild Project

```bash
gradle build
```

---

## 📤 Sample Output

```text
CodeAlpha Gradle Project Running Successfully
Created by Sahil Shaikh
```

---

## 📚 Learning Outcomes

Through this project, I learned:

- Java application development
- Gradle project structure
- Build automation concepts
- Dependency management
- Build lifecycle
- Source code compilation
- Git and GitHub workflow
- DevOps development practices

---

## 🔄 Build Lifecycle Understanding

The Gradle build process includes:

1. Initialization Phase
2. Configuration Phase
3. Execution Phase

Common tasks executed:

- compileJava
- processResources
- classes
- jar
- build
- run

---

## 🚀 Future Enhancements

- Add external dependencies
- Implement unit testing
- Integrate CI/CD pipeline using Jenkins
- Deploy application using Docker
- Publish artifacts automatically

---

