# Ascentt-GPT 

## Overview 

Ascentt-GPT is a sophisticated multilingual chatbot offering secure, responsive, and context-aware assistance globally. Its advanced features address a wide range of user needs and scenarios, exceeding the capabilities of traditional chatbots. 

### Project Description 

Ascentt-GPT is a state-of-the-art, multilingual chatbot that offers highly interactive, secure, and dynamic conversations. Designed to meet the 	diverse needs of users across various industries, it ensures accurate and relevant responses by integrating real-time data sources and advanced technologies. Its capabilities extend beyond traditional text-based communication, allowing it to process both text and images for more context-rich and versatile interactions. It is built with a strong focus on privacy and security, providing a safe environment for users while adhering to compliance standards. Its intuitive interface makes it accessible to users of all technical levels, making it an invaluable tool for businesses looking to enhance user engagement and operational efficiency. 

 

## Architecture 

### Overview 

#### 1. Frontend Layer: 

Single Page Application (SPA): The frontend is developed using HTML, CSS, and JavaScript to create a dynamic and engaging user interface.  

WebSocket Communication: The SPA ensures real-time 				interaction and seamless user experience through WebSocket 			protocols for two-way communication. 

 

#### 2. Backend Layer 

Application Servers: The backend employs Flask to manage API 		endpoints securely and efficiently. It integrates various external APIs, 	such 	as Weather API, Google Search, and Wikipedia, to provide dynamic 		responses. 

#### 3. Security and Compliance 

Authentication and Authorization: User access is safeguarded through robust authentication mechanisms. Role-based access control ensures only authorized users can access specific functionalities. 

Data Encryption: Sensitive data is encrypted both at rest and in transit, adhering to compliance standards and protecting user information. 

 

## Infrastructure 

### Infrastructure Overview 

Ascentt-GPT is hosted on a scalable and reliable cloud computing 				platform to ensure high availability and performance. 

 

* Cloud Computing Platform: AWS services form the backbone of the 		infrastructure, offering scalability and robust management tools. 

* Data Storage Management: Data is stored securely using AWS’s 		managed storage solutions, which ensure redundancy and durability. 

* AI and ML Infrastructure: The platform leverages powerful AI/ML 		capabilities from 	AWS services to process queries efficiently and 		accurately. 

* SPA and WebSocket Integration: The seamless integration of SPA with 	WebSocket protocols ensures real-time communication and an interactive 	user experience. 

* Monitoring and Maintenance: The infrastructure is monitored using 	AWS 	CloudWatch and other tools to ensure uptime and quick resolution of 	issues. 

 

## User Interface and Experience 

 

## Tools: 

* AWS for hosting and cloud services. 

* Docker for containerization. 

* Environment Setup: 

* Set up an AWS account. 

* Configure EC2 instances for hosting. 

* Use Docker for containerized deployment. 

## Features and Functionality 

## Features 

### Multilingual Support: 

* Description: Provides interaction in multiple languages to 		enhance accessibility. 

* Functionality: Implements query blocking, anonymization, and 	positive-response generation. 

 

### Safeguard Layer: 

* Description: Ensures security and compliance by monitoring 			queries for sensitive information or malicious intent. 

* Functionality: Implements query blocking, anonymization, and 	positive-response generation. 

 

### Real-Time Data Integration: 

* Description: Accesses real-time data using external APIs. 

* Functionality: Fetches weather information, web results, and factual data dynamically. 

 

### Versatile Interaction: 

* Description: Able to process text, audio, image, and pdf 			queries, providing comprehensive interaction options. 

* Functionality: Uses LLM for images, PyPDF for PDFs and for voice it 	uses WebKit Speech Recognition. 

 

### Image Generation and Fetching: 

* Description: Allows you to generate images and fetch images based 	on your query. 

* Functionality: For generation of images, Stable Diffusion is used and 	for fetching scraping is done. 

 

 

 

### PII Masking: 

* Description: Hides PII information whenever query response is provided by the chatbot. 

* Functionality: Prompt Enhancement, restrict display any PII information to adhere Safeguard Layer. 

 

 

## Application Setup 

### Development Tools: 

* HTML, CSS, JavaScript for front-end development. 

* Flask for backend framework. 

* Spacy for NLP processing. 


 


 
