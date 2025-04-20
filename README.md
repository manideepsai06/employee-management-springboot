# 🚀 Employee Management System (Spring Boot)

This project is a simple yet production-ready **CRUD web application** that allows you to **Create, Read, Update, and Delete** employee details using the **Java Spring Boot** framework.

🎓 Designed to be beginner-friendly and perfect for students exploring Java backend development!

---

## 🛠️ Tools & Technologies

- **Java** – 17  
- **Spring Boot** – 3.2.4  
- **Maven** – 3.9.9  
- **Database** – H2 (In-Memory)  
- **Frontend** – Thymeleaf + Bootstrap 5

---

## ⚙️ Setup Instructions (Run App Locally)

### ✅ Step 1: Install Chocolatey (Windows only)

     Set-ExecutionPolicy Bypass -Scope Process -Force;  
     [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.SecurityProtocolType]::Tls12;  
     iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

### ✅ Step 2: Install Java JDK 17
     
       choco install openjdk17 -y
       #to check java version
       java -version

### ✅ Step 3: Install Maven

        choco install maven -y
        #Verify Maven:
        mvn -v    
        
### ✅ STEP 4: Setup Spring Boot App

        #first install Git
        choco install git -y
        #For cloning repo
        git clone https://github.com/manideepsai06/employee-management-springboot.git
        #to move to project folder
        cd employee-management-springboot

### ✅ STEP 5: Run the Spring Boot Application

        mvn clean install 
        #to run application
        mvn spring-boot:run

# After running app test the app by
Opening this url in your browser: http://localhost:8080  
- for database access open url : http://localhost:8080/h2-console  
  set jdbc url to : jdbc:h2:mem:testdb

Happy Execution!!!
