## Project-Explaination
 1. Jenkins job should automatically get triggered when code is commited in github
 2. Use maven as a build automation tool to build war file
 3. Delete existing war file in remote server & Transfer war file to Remote server - where tomcat-docker compose file exists
 4. Execute commands in Remote server 'docker compose down' & 'docker compose up -d'
 5. Updated war file should be reflected in tomcat container
Automate all the above explaination in Jenkins Pipeline

## Pipeline Over-view

![Screenshot 2022-09-21 at 15-55-41 new Jenkins](https://user-images.githubusercontent.com/98376417/191481497-64b27d9e-5155-47ef-91dd-dae3177c7f16.png)


## Project-Flow

![P1(1)](https://user-images.githubusercontent.com/98376417/191477390-835401d0-d4b1-47a0-8e62-d05a3c314521.png)


