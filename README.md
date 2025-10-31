# react-docker-multistage
Dockerized React application using a multi-stage build process. The Node.js stage installs dependencies and builds optimized static files, while the Nginx stage serves them in production. This setup reduces image size, improves performance, and ensures clean separation of build and runtime.
