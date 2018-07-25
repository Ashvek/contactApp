# Contact Directory App
This application is build using Angular 6 and Bootstrap 4

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You must have Node JS and Npm installed on your system. If not installed then follow below steps

```
https://nodejs.org/en/download/
```

### Installing

Next Step is download the zip folder extract it and visit to the directory inside cmd/terminal and run

```
npm install
```

this will install all the node modules dependencies along with angular 6 cli node moduels. Once completed run bellow command to start the application

```
ng serve --open
```
This will Open the applpication on hhttp://localhost:4200/  by default if port is free.

NPM JSON-Server is installed for API Calls. 

REST API Url is set in src/environments/environment.ts and src/environments/environment.prod.ts files so we can change the api url for production and developement mode. 

```
apiUrl: 'http://localhost:3000'
```
Start json-server from cmd/terminal

```
npm run json-server
```
## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Angular 6 uses Karma and Jasmine inorder to run the unit test enter following command 

```
ng test
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Angular 6](https://angular.io/) - The Javascript framework used
* [Bootstrap 4](https://getbootstrap.com/) - Layout and Design framework used

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Ashvek Gaonkar* - *Initial work* - [Contact App](https://github.com/Ashvek/contactApp)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to angular 6 https://angular.io/tutorial
* Inspiration
* etc
