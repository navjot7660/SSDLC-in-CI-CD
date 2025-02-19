# 🚀 SSDLC in CI/CD Pipeline  

## **📌 Overview**  
This project demonstrates the integration of **Secure Software Development Lifecycle (SSDLC)** within a **CI/CD pipeline**. It ensures that security best practices are applied at every phase of development, using automated security tools to detect vulnerabilities before deployment.  

## **🛠 Tech Stack & Security Tools**  
- **CI/CD Pipeline:** Jenkins  
- **Version Control:** GitHub  
- **Static Code Analysis (SAST):** SonarQube  
- **Dependency Scanning:** OWASP Dependency Checker  
- **Dynamic Application Security Testing (DAST):** OWASP ZAP  
- **Secret Scanning:** TruffleHog  
- **Vulnerability Management:** DefectDojo  

## **🔍 SSDLC Security Phases in CI/CD**  

| **Stage**    | **Security Integration**  | **Tool Used**  |
|-------------|--------------------------|---------------|
| **Planning**  | Threat Modeling, Security Requirements | N/A |
| **Development** | Secure Coding, Dependency Scanning | OWASP Dependency Checker |
| **Build & Test** | Static Code Analysis (SAST) | SonarQube |
| **Pre-Deployment** | Dynamic Testing (DAST) | OWASP ZAP |
| **Deployment** | Security Policies Enforcement | Jenkins Security Plugins |
| **Post-Deployment** | Monitoring & Vulnerability Management | DefectDojo |

## **🛠 Setup Instructions**  

### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/navjot7660/SSDLC-in-CICD.git
cd SSDLC-in-CICD
