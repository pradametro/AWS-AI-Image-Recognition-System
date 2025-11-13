# ☁️ AWS AI Image Recognition System ☁️

This project is built on fully serverless architecture, and leverages Amazon Rekognition to analyze images and identify objects, scenes, and concepts. The detected results are then sent to Amazon Bedrock (Titan model), which generates a clear, human readable summary. The frontend enables users to upload images and instantly receive AI generated descriptions.

---

## Features
- Image upload interface built with HTML, CSS, and JavaScript.
- Uses Amazon Rekognition to identify objects, people, and scenes in images.
- Uses Amazon Bedrock (Titan model) to generate a human readable description based on detected labels.
- Backend powered by an AWS Lambda function written in Python.
- Terraform automates AWS infrastructure deployment for consistency and scalability.
- Frontend hosted on Amazon S3 for public access.

---

## Tech Stack:
- Amazon Rekognition: Detects objects, scenes, and labels in images
- Amazon Bedrock (Titan): Converts labels into descriptive text using generative AI
- AWS Lambda (Python): Processes requests and orchestrates AI services
- Amazon API Gateway: Exposes our backend via a RESTful API
- Amazon S3: Hosts a static frontend (HTML/CSS/JS)
- Terraform: Provisions the full infrastructure as code (IaC)

---

## How It Works
1. A user uploads an image through the web interface.
2. The image is sent to AWS Lambda via API Gateway.
3. Rekognition analyzes the image and detects labels with confidence scores.
4. Bedrock generates a natural language description of the image.
5. The labels and description are displayed on the website in real time.

---

## Try it for yourself!
[View the AI Image Analyzer](https://ai-image-analyzer-frontend-2c267705188025b1.s3.us-east-1.amazonaws.com/index.html)

---

## Contact Information
For questions, feedback, or support requests, please contact mailto.ccvirakboth12@gmail.com

**Virakboth Chau**  
George Mason University | Information Technology Major  
[LinkedIn Profile](https://www.linkedin.com/in/virakboth-chau/)
