# Smart City - Outdoor Sports Navigator

This project is a real-time outdoor activity dashboard designed to enhance the outdoor experience for urban residents. Built with Node-RED and MongoDB, it visualizes critical data such as weather forecasts, air quality, and immigration statistics through dynamic charts and interactive maps.

## Features

- **Real-Time Data Visualization**: Displays up-to-date weather forecasts, air quality indices, and immigration data using visually appealing charts and maps.
- **API Integration**: Utilizes APIs from the Hong Kong Observatory to fetch essential meteorological and environmental data.
- **User-Friendly Dashboard**: Constructed in Node-RED, making it easy to navigate and interact with various data points.
- **Deployment**: The application is deployed on Alibaba Cloud, leveraging Elastic Compute Service (ECS) for hosting and Docker for containerization.

## Technologies Used

- **Node-RED**: A powerful tool for visual programming and data integration.
- **MongoDB**: Used for efficient data storage and management.
- **Docker**: For containerization, ensuring the application runs consistently across different environments.
- **APIs**: Integrated data sources from the Hong Kong Observatory.

## Prerequisites

- A Linux environment is required to run this project.
- Docker must be installed on your machine.

## Quick Start

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/Smart-City-Outdoor-Sports-Navigator.git
   cd Smart-City-Outdoor-Sports-Navigator

2. **Import the Flow**:
   
    Open Node-RED in your browser (usually at http://localhost:1880).
    Click on the menu in the top right corner, select "Import", and then paste the contents of flow.json into the import dialog.
    Click "Import" to add the flow to your workspace.
   
3. **Deploy the Application**:
   
    Ensure Docker is running and your MongoDB instance is set up and accessible.
    Deploy the flow in Node-RED by clicking the "Deploy" button.
  
4. **Access the Dashboard**:
    Navigate to the dashboard URL provided by Node-RED to view and interact with the dashboard.
