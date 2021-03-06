# StackOverflow-lite

StackOverflow-lite is a platform where people can ask questions and provide answers.


## Getting Started

Clone the project using the [link](https://github.com/KengoWada/Stackoverflow-lite).

### Prerequisites

A browser with the access to the internet.

### Installing

* Clone the project to your local machine
```
git clone https://github.com/KengoWada/Stackoverflow-lite.git
```

### Features

* Post a question
* Post an answer for a particular question
* Get all questions
* Get a single question


### Endpoints

HTTP Method|Endpoint|Functionality
-----------|--------|-------------
POST|api/v1/questions|Create a question
GET|api/v1/questions/questionId|Fetch a specific question
GET|api/v1/questions|Fetch all questions
POST|api/v1/questions/questionId/answers|Add an answer


### Tools Used

* [Flask](http://flask.pocoo.org/) - Web microframework for Python.
* [Virtual Environment](https://virtualenv.pypa.io/en/stable/) - Used to create isolated Python environments
* [PIP](https://pip.pypa.io/en/stable/) - Python package installer.

### Built With

* Python/Flask

### Authors

Kengo Wada