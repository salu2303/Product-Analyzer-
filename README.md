# Serverless Product Analyser

Welcome to the Serverless Product Analyser project! This serverless web application utilizes AWS DynamoDB, AWS Lambda, AWS API Gateway, and ReactJS to deliver an in-depth review analysis system for over 3 million Amazon products.

## Technologies Used

- **ReactJS:** A JavaScript library for building user interfaces.
- **AWS DynamoDB:** A fully managed NoSQL database service by AWS.
- **AWS Lambda:** A serverless compute service for running code without provisioning or managing servers.
- **AWS API Gateway:** A fully managed service for creating, publishing, and securing APIs.

## Project Overview

The goal of this project is to provide a high-performance and user-friendly system for analyzing reviews of Amazon products. Key features and achievements include:

- **Efficient Data Storage:**
  - Utilizes AWS DynamoDB for storing data related to over 3 million Amazon products.

- **Serverless Architecture:**
  - Leverages AWS Lambda for backend logic, ensuring scalability and cost-effectiveness.

- **RESTful API:**
  - Implements a RESTful API using AWS API Gateway, enabling seamless communication between the frontend and backend.

- **User Interface:**
  - Built with ReactJS to offer an intuitive and responsive user interface.

- **Query Performance Optimization:**
  - Achieved a 45% reduction in response time for queries in AWS DynamoDB through strategic calibration of read and write capacity.

- **Resource Utilization Optimization:**
  - Optimized resource utilization, resulting in a 30% increase in efficiency and driving overall cost-effectiveness.

## Getting Started

Follow these steps to run the project locally:

### Prerequisites

- Node.js and npm installed
- AWS account with necessary permissions
- AWS CLI configured on your machine

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/serverless-product-analyser.git

## Configuration

### AWS Configuration:
- Update the AWS credentials in the ~/.aws/credentials file with your AWS access key and secret key.

### Frontend Configuration:
- Navigate to the client directory and create a .env file.
- Set the necessary environment variables, such as REACT_APP_API_ENDPOINT for your AWS API Gateway endpoint.