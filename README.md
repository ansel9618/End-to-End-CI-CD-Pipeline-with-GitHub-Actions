
### **Summary: End-to-End CI/CD Pipeline with GitHub Actions**  
The code demonstrates how to build a **complete CI/CD pipeline** using **GitHub Actions** for a **Flask application**. The workflow includes:  

1. **Continuous Integration (CI):**  
   - Develop a Flask app with unit tests (using **Pytest**).  
   - Automatically trigger **build and test** on code push to the main branch.  
   - Create a **Docker image** for the app (Linux-based container).  

2. **Continuous Deployment (CD):**  
   - Deploy the validated Docker image to **Docker Hub** (public repository).  
   - Use **GitHub Secrets** to securely store Docker Hub credentials (username + access token).  

3. **Tools Used:**  
   - **Git/GitHub** (version control & repository).  
   - **Docker** (containerization).  
   - **Pytest** (testing).  
   - **Flask** (web framework).  

### **Key Takeaways:**  
- Fully automated process (no manual steps).  
- Covers both **CI (testing/building)** and **CD (deployment)**.  
- Demonstrates **secret management** for secure deployments.  

