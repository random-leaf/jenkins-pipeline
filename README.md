# Building and Running the Docker File for Dev App

## Prerequisites
- Docker must be installed and running on your system.

## Steps to Build and Run

1. **Build the Docker Image**  
   Run the following command to build the Docker image:

   ```bash
   docker build -t leafhub:latest .
   ```

2. **Run the Docker Container**
   After building the image, run the following command to start the container

   ```bash
   docker run -d -p 80:80 leafhub
   ```
   
3. **Verifying the Application**
   Open a web browser and navigate to 'http://PublicIP/leaf' to verify the application is running successfully.
