# Java Application Deployment with Reverse Proxy on AWS

## Objective
Deploy a Java-based Student Registration Web Application on AWS using Apache Tomcat, Amazon RDS MySQL, and Apache Reverse Proxy.

---

## Technologies Used
- AWS EC2
- Apache Tomcat
- Apache HTTPD
- Amazon RDS MySQL
- Java
- Linux

---

## Architecture
Client → Apache Reverse Proxy → Tomcat Backend → Amazon RDS

---

## Features
- Secure reverse proxy setup
- Backend server protection
- Database integration
- Restricted backend access using Security Groups
- Student registration data storage in RDS

---

## Backend Setup Commands

### Install Java
```bash
sudo yum install java-1.8.0-openjdk -y
```

### Check Java Version
```bash
java -version
```

### Download Tomcat
```bash
wget https://downloads.apache.org/tomcat/
```

### Start Tomcat
```bash
./startup.sh
```

### Start Tomcat
```bash
./startup.sh
```
