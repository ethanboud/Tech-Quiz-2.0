# Tech Quiz 2.0 CI/CD
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description
This takes an already made web application for a simple programming language quiz and implements the use of github actions for testing purposes and for automated deployment. 

## Table of Contents
- [Tech Quiz 2.0 CI/CD](#tech-quiz-20-cicd)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contribution](#contribution)
  - [Test](#test)
  - [License](#license)
  - [Questions](#questions)

## Installation
Fork the repository and create a develop branch. It is recommended to create branch checks/security for pushes on the main and develop branches. Once ready, create a feature branch. Lastly, link this repository with Mongo Atlas, and additionally link it with a Render web service ready for deployment, but turn OFF the auto deploy option. 

## Usage
Once the above items have been taken care of, try making an addition or a change to the quiz component. For example, change the word "quiz" with "test" for "start quiz". Commit these changes and push to the develop branch. Initiating a push to the develop branch will trigger a github action to take place thanks to the yml files in the repository. With this change, it should cause the github action test to fail, presenting a warning to merging the branch. Change the "test" back to "quiz" and commit and push again. This should cause the github actions to now pass. Once complete, push the changes from the develop branch to the main branch. Any push to the main branch will trigger the application to be deployed/re-deployed on Render. 

## Contribution
Feel free to fork this repository and use it to craft your own CI/CD web applications. If you have any tips or advice on how this can be improved feel free to reach out to my email as listed below. 

## Test
For quickest and easiest testing, fork the repo, create a develop branch, create a feature branch. Make changes or additions to the code in the feature branch, then push to the develop branch as this will trigger a github  action. This will only test the github action pertaining to pushing to the develop branch, to test the main branch, linking the repository to mongo atlas and a web service on render will be required. The github action will still run, but it will not be able to complete the "deploy" script if this is not completed. 

## License
        This project is licensed under the MIT license.
[MIT](https://opensource.org/licenses/MIT)
    

## Questions
If you have any questions, please contact me at ethanboud@gmail.com(mailto:ethanboud@gmail.com) or visit my GitHub profile ethanboud