# SirenJobs
Job listing React/Node app w/ GraphQL implementation for multi-variable querying 

## Objectives

$ List jobs with their company, job title, location, and the first 100 characters of the job description 
-> POST Job

$ Job listing should be filterable by company, level, location, and job category, a user should be able to filter on multiple values and multiple facets. 
→ SEARCH/FILTER Jobs

$ Clicking the job title to be able to see the full details of a specific position 
→ MORE button to reveal rest of description

$ Search for a job by title only
→ ElasticSearch for Jobs

$ Ingest data at the command line or via a web page either from flat files or the API listed below
→ CONSUME THE MUSE API



## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

```
npm 6.7.0
```

### Installing
From the command terminal, clone the repository to your local directory...
```
$ git clone https://www.gihub.com/izzydoesit/sirenJobs.git
$ cd sirenJobs
```

Then run yarn (or npm equivalent) commands to install all dependencies and start the server.  

```
$ npm install
$ node server.js
```

## Deployment

You must have Heroku CLI installed and be logged in to Heroku in order to deploy live via Heroku servers
(Please see the [documentation](https://devcenter.heroku.com) to get set up with Heroku)

Then, after installation and login to Heroku CLI, via the command line...
```
heroku create -b https://github.com/mars/create-react-app-buildpack.git
git add .
git commit -m "react-create-app on Heroku"
git push heroku master
heroku open
```
## Built With

* [GraphQL](https://graphql.org/) - Server side runtime for executing queries
* [React](https://facebook.github.io/react) - Front end JavaScript framework used
* [Material UI](https://material-ui.com/) - UI library for React that implements Google's Material Design
* [Express](https://expressjs.com/) - Node web application framework
* [JSON-Server](https://github.com/typicode/json-server) - REST API server w/ fake data (for dev)
* [Axios](https://github.com/axios/axios) - Promise-based HTTP client

## Author

* **Israel Matos** - [Github](https://github.com/izzydoesit)

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE.md](LICENSE.md) file for details


## Available Scripts

In the project directory, you can run:

### `json:server`

Runs the fake json server that serves as an external API.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run dev`

Launches the Express server with Nodemon for automatic server restart on file changes
