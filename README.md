PROJECT TITLE:
Nike Landing Page – CI/CD Automation and Cloud Deployment using Microsoft Azure


PROJECT OVERVIEW:
This project focuses on implementing a complete CI/CD pipeline and cloud deployment workflow for a frontend web application. 
The frontend (Nike Landing Page UI) is used as a sample application, while the primary ownership of this project is on DevOps automation, artifact management, and Azure cloud deployment.


PROJECT OBJECTIVE:
The objective of this project is to demonstrate real-world DevOps practices by automating the build, artifact versioning, and deployment process using Azure DevOps and Microsoft Azure services.


NOTE ON CODE OWNERSHIP:
The frontend UI code is used as a sample/static application for deployment purposes.
The main contribution in this project is the CI/CD pipeline design, artifact lifecycle management, and cloud hosting configuration.


TECHNOLOGIES USED:

Frontend (Sample Application):
- HTML
- CSS
- JavaScript
- Tailwind CSS

DevOps & Cloud:
- Azure DevOps (CI/CD Pipelines)
- Azure Artifacts (Centralized Artifact Feed)
- Azure App Service (Linux)
- Node.js
- Git & GitHub


ARCHITECTURE FLOW:

Developer Code Repository
        |
        v
Azure DevOps CI Pipeline
        |
        v
Build Frontend Application
        |
        v
Artifact Generated (dist folder)
        |
        v
Artifact Published to Azure Artifacts (Versioned)
        |
        v
CD Pipeline Downloads Artifact
        |
        v
Deployment to Azure App Service
        |
        v
Live Web Application


CONTINUOUS INTEGRATION (CI):
- Pipeline is automatically triggered on code changes
- Installs required dependencies
- Builds the frontend application
- Generates production-ready build output
- Publishes build artifacts to a centralized Azure Artifacts feed


CONTINUOUS DEPLOYMENT (CD):
- Downloads the approved artifact version
- Packages the artifact as a ZIP file
- Deploys the artifact to Azure App Service (Linux)
- Ensures consistent deployment using the same artifact without rebuilding


ARTIFACT MANAGEMENT:
- Uses Azure Artifacts (Universal Packages)
- Each build produces a new immutable artifact version
- Supports traceability, rollback, and controlled promotion


DEPLOYMENT DETAILS:
- Hosted on Microsoft Azure App Service (Linux)
- ZIP-based automated deployment
- Publicly accessible web application

LIVE APPLICATION URL:
https://nike-landing--page-aud8fhf7fucnczet.centralindia-01.azurewebsites.net/


KEY DEVOPS LEARNINGS:
- CI/CD pipeline implementation using Azure DevOps
- Centralized artifact feed usage and versioning
- Automated deployment to Azure cloud
- Understanding of CI vs CD responsibilities
- Real-world troubleshooting of deployment issues


INTERVIEW EXPLANATION (SAFE & PROFESSIONAL):
This project demonstrates how a frontend application can be automatically built, versioned, and deployed using Azure DevOps pipelines and Azure cloud services. The primary focus is on DevOps automation, artifact management, and deployment strategy rather than frontend development.


POSSIBLE FUTURE IMPROVEMENTS:
- Migration to Azure Static Web Apps
- Multi-environment deployment (Dev, QA, Prod)
- Approval gates and release validations
- Automated testing integration
