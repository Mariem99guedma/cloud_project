

This is a simple web application. It has working user registration, login page and there is a complete example of CRUD which contains example for Angular Routing and dotnet rest api samples. Also, rest services are secure using JWT. 

Below is the architecture of the application while it is running.


## To Quick Run
Clone repo, navigate to root folder and run ` docker-compose -f 'docker-compose.yml' up`
#### Development mode:
  You can start the application in debug mode (database, api and frontend) using docker-compose:

  ```
  
  cd angular-dotnet 
  
  docker-compose -f 'docker-compose.debug.yml' up
  ```

  It will run fronend `http://localhost:4200` and api on `http://localhost:8080`. you can also access PGAdmin  on port 5050 with username pssword provided in docker-compose, username: nitin27may@gmail.com, password: root.

  Also, it will automatically refresh (hot reload) your UI for code and api code changes.
