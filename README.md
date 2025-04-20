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
     
Command : choco install openjdk17 -y
Verify Java: 
Command : java -version

### ✅ Step 3: Install Maven
        ```powershell    
        Command : choco install maven -y
        Verify Maven:
        command : mvn -v 
        powershell ```    
        
STEP 4: Setup Spring Boot App
        first install Git
        Command : choco install git -y
        Then : 
        Command : git clone [https://github.com/YOUR_USERNAME/employee-management-springboot.git](https://github.com/manideepsai06/employee-management-springboot.git)
                  cd employee-management-springboot

STEP 5: Run the Spring Boot Application
        From the project folder: 
        Command : mvn clean install 
                  ![image](https://github.com/user-attachments/assets/1b39a258-20e7-4dbf-a000-3d7cd9457f4a)
                  mvn spring-boot:run

# After running app test the app by
Opening this url in your browser: http://localhost:8080
- for database access open url : http://localhost:8080/h2-console
               set jdbc url to : jdbc:h2:mem:testdb

Happy Execution!!!
