# 2019 Novel Coronavirus

Wednesday 29th January 2020, the Novel Coronavirus was declared a Global Health Emergency by the World Health Organisation [(WHO)](https://www.who.int/emergencies/diseases/novel-coronavirus-2019 'World Health Organisation'). On the 7th February 2020 the number of confirmed cases were 31,485 in over 28 countries, which has risen to 71,811 by 17th February 2020 (ie over 128% in 10 days).

This project is to build an information hub for the 2019 novel coronavirus. This hub will contain interactive dashboard that gives a real-time visualization on the coronavirus and up-to-date information on its prevention.

[![Corona Virus](http://img.youtube.com/vi/mOV1aBVYKGA/0.jpg)](http://www.youtube.com/watch?v=mOV1aBVYKGA "source: World Health Organisation")

## Table of contents

- [Getting Started](#getting-started)
- [Technology](#technology)
  - [Prerequisites](#prerequisite)
  - [Built With](#built-with)
  - [Installing](#installing)
    -[Frontend](#frontend)
    -[Backend](#backend)
- [How to Contribute](#how-to-contribute)
- [Acknowledgement](#acknowledgment)
  - [Inspiration](#inspiration)
  - [Data Source](#resource)
- [License](#license)

## Getting Started

These instructions will get a copy of the project up and running on your local machine for development and testing purposes. See ['how to contribute'](#contribute) for notes on contributing to the project.

## Technology

The following software needs to be installed.

### Prerequisite

- [Python 3.5 and later](https://www.python.org/)
- [Node JS](https://nodejs.org/)
- [Typescript](https://www.typescriptlang.org/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Other dependencies](./requirements.txt)
- [Google Cloud Platform](https://cloud.google.com/)

### Built With

- [Angular](https://angular.io/)
- [D3js](https://d3js.org/)
- [Django](https://www.djangoproject.com/)

### Installing

#### Frontend

1. Install all dependencies
  ```npm install```

2. Start server
  ```ng serve```

#### Backend

**Create a virtual environment.**
Use **virtualenv** to create a virtual environment for the project, Run the following in your terminal.

1. Install virtualenv using pip3.
  ```pip3 install virtualenv```

2. In the root of the project, create a virtual environment.
  ```virtualenv workspace```

3. Activate workspace.
  ```source/workspace/bin/activate```

**Install the dependences**
Run the requirement.txt on the activated workspace
  ```pip install -r requirement.txt```

**Run the backend server**
Run manage.py in the backend folder

  ```python
  cd backend
  python manage.py runserver
  ```

## How to contribute

You can contribute to the project and make it better. It is an open source project. Improve the code and send in a pull request with your contributions.

[Here is how to send in a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

If sending pull requests are not your thing, you can send me a tweet @SolomonIgori or email at [igorisolomon@gmail.com](igorisolomon@gmail.com "Igori's email")

<!-- 
Please read [CONTRIBUTING.md](https://github.com/igorisolomon/coronavirus/blob/master/CONTRIBUTING) for details on our code of conduct, and the process for submitting pull requests to us.
See also the list of [contributors](https://github.com/igorisolomon/coronavirus/blob/master/contributors) who participated in this project. -->

## Acknowledgment

### Inspiration

- [Johns Hopkins University Dashboard](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html?fbclid=IwAR2mWEw0X_B5jbR0Fm23t2TVJGzVqUY6ok98DzrGLMrMXCR_c5joZV5AdNU#/bda7594740fd40299423467b48e9ecf6)

### Resource

- [World Health Organization (WHO)](https://www.who.int/)
- [Observable](https://observablehq.com/@fil/ncov2019-data)
- [Johns Hopkins University Data Source](https://docs.google.com/spreadsheets/d/1UF2pSkFTURko2OvfHWWlFpDFAr1UxCBA4JLwlSP6KFo/htmlview?sle=true#)

## License

The project is licensed under the MIT license. See [LICENSE.md](https://github.com/igorisolomon/coronavirus/blob/master/LICENSE 'MIT License') for more information.
