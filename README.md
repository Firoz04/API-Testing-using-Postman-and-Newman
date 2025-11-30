# API Testing using Postman & Newman 🚀

This repository contains a comprehensive suite for API testing using **Postman** and **Newman**. It’s designed to automate testing of RESTful APIs — enabling test execution, validation of response codes, response content and headers — thereby ensuring API reliability and stability before deployment.

## 📄 What’s Inside  
| File / Folder | Description |
|---------------|-------------|
| `allAPItesting.postman_collection.json` | The main Postman Collection containing all API requests and test scripts. |
| `newman/` | Contains scripts / configuration for running tests via Newman CLI. |
| `.gitattributes` | Git attributes configuration. |
| `README.md` | Project documentation (this file). |

## ✅ Why This Project Matters  
- Automates API testing — no more manual requests for every change.  
- Ensures consistency and repeatability when testing APIs.  
- Useful as a template when starting testing for new APIs.  
- Easy integration into CI/CD pipelines via Newman or other automation tools.

## 🚀 Getting Started (Quick Setup)  

### Prerequisites  
- Node.js (v14+ recommended)  
- Newman (install globally or via npm)  
- Postman (for interactive testing)  

### Installation & Running Tests  

```bash
# Clone the repository
git clone https://github.com/Firoz04/API-Testing-using-Postman-and-Newman.git  
cd API-Testing-using-Postman-and-Newman  

# If you want to run with Newman:
npm install -g newman   # (if not installed)  
newman run allAPItesting.postman_collection.json
