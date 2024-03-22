# LearningEKS
### Architecture Diagram
!(Architecture Diagram)[./architecture.jpg]

### Steps
1. Download Apache web server image
2. Add your web page or html file to the web server and create a new image using Docker. 
3. Push the new image to Docker hub
4. Create a EKS cluster with 2 or more nodes for high availability
5. Create services and deployment using new image on every Kuberenetes pod
