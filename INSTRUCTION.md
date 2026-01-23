# Project Instructions

### Docker Hub Repository
You can find the images here:
`docker pull nickptrnko/mysql-local:latest`
`docker pull nickptrnko/todoapp:2.0.0`

### Run the MySQL Container
To run MySQL container with a volume attached, execute the following command:
```
docker run  -d -p 3306:3306 --name <your_contaynar_name> -v <your_volume_name>:/var/lib/mysql mysql-local:1.0.0
```

### Run the App Container
Execute the following command to start the app:
```
docker run -p 8080:8080 todoapp:2.0.0
```
### Accessing the Application
Once the containers is running, open your browser and navigate to: http://localhost:8080
