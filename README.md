# C# Docker Example

This repository contains a simple C# application configured to run inside a Docker container. The setup demonstrates how to prepare the application for both development and production environments using Docker. This approach ensures that the application runs consistently across different stages, reducing "works on my machine" issues and simplifying deployment processes.


For development:
'docker-compose -f docker-compose.dev.yml up --build'


For production:
'docker-compose -f docker-compose.prod.yml up --build'
