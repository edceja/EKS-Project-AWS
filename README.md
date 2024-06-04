# EKS-Project-AWS
Repository for all AWS EKS project code 

Phase 4 capstone project posed by the folks at [Learn to Cloud](https://learntocloud.guide/). 

Sample application (frontend and backend) from [rishabkumar7](https://github.com/rishabkumar7/devops-qr-code/tree/main). 

## Architecture and Functionality 

An AWS EKS cluster with 2 nodes. The front end deployment consists of a containerized Node.js application, a corresponding service and an ingress resource. Similarly, the backend
is a containerized FastAPI Python application running a Uvicorn server. The backend also has a corresponding service and ingress resource.  

The webapp and API accessed from the browser through an application load balancer installed on the EKS cluster. The user inputs a valid URL and QR code is generated and displayed to the user. The QR code image is stored in a S3 bucket (uploaded by the backend).  

