# AWS EC2 Automation with Ansible  

This project demonstrates how to automate the provisioning and management of AWS EC2 instances using **Ansible**.  

We tackled several tasks to explore **infrastructure automation, configuration management, and conditional orchestration**.  

---

## 🚀 Tasks Completed  

### **Task 1 – Provision EC2 Instances with Ansible Loops**  
- Created **3 EC2 instances** using Ansible loops:  
  - **1 AWS Ubuntu instance**  
  - **2 regular Ubuntu instances**  
- Used `connection: local` on the Ansible control node to interact with AWS API.  

### **Task 2 – Configure Passwordless Authentication**  
- Set up **passwordless SSH authentication** between the Ansible control node and the newly created EC2 instances.  
- Simplified management by enabling direct access without repeatedly providing keys.  

### **Task 3 – Automate Shutdown of Ubuntu Instances Only**  
- Automated shutdown for **Ubuntu instances only**.  
- Implemented **Ansible conditionals** with `when` based on `ansible_facts` gathered at runtime.  
- Ensured AWS Ubuntu instance (or other non-Ubuntu instances if any) remained unaffected.  

