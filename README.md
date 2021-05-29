# Phone CRUD

The goal of this project is to have a web interface to view and edit records on a database. This project includes a frontend and a backend, referenced as external repositories. 

### Project structure

The web interface is a React App, you can find the source code and its documentation on the following link:
[phone-crud-frontend](https://github.com/balb0x/phone-crud-frontend)

For the backend the project uses python flask to publish an API rest interfacing with a MongoDB Database. The source code and documentation is found here:
[phone-crud-backend](https://github.com/balb0x/phone-crud-backend)

For a more detailed information of the components of the projects, follow the links. 


### Deployment

The entire project is Docker friendly, so it can be deployed running the following line to build it:

``` 
docker-compose build 
```

And the next one to run it:

``` 
docker-compose up
``` 

The docker container runs 3 services, a mongo instance and the frontend/backend repositories:

- The backend exposes the API Rest on port `5000`

- The frontend exposes the web app on port `3000`

- The database is handled in the container