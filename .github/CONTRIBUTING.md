# Contributing

## How to contribute

Support and contributions from the open source community are essential for keeping
Mean Stack JS up to date. We are always looking for the quality contributions and 
will be happy to accept your Pull Requests as long as those adhere to some basic rules:

* Please make sure that your contribution fits well in the project's style & concept:
  * [Standard JS](http://standardjs.com/)
  * [Pass All Test](https://travis-ci.org/greenpioneersolutions/mongoose-xlsx-data-importer)

## Creating an Issue

Before you create a new Issue:
* Check the [Issues](https://github.com/greenpioneersolutions/mongoose-xlsx-data-importer/issues) on Github to ensure one doesn't already exist.
* Place use one of these topics in the beginning of your issue title- Contrib, Hotfix, Error, Help or Feature.
* Clearly describe the issue, including the steps to reproduce the issue.
* If it's a new feature, enhancement, or restructure, Explain your reasoning on why you think it should be added, as well as a particular use case.

## Making Changes

* Create a topic branch from the development branch with the issue number EX. `#200_make_changes`
* Use `standard || npm run standard` to verify your style - `npm install -g standard` if you dont have it already
* Keep git commit messages clear and appropriate
* Make Sure you have added any tests necessary to test your code. `npm test`
* Update the Documentation to go along with any changes in functionality / improvements.

## Submitting the Pull Request

* Push your changes to your topic branch on your fork of the repo.
* Submit a pull request from your topic branch to the development branch
* We use [GitFlow](https://guides.github.com/introduction/flow/)
* Be sure to tag any issues your pull request is taking care of / contributing to. EX. `#201 add and updated this`
  * By adding "Closes #xyz" to a commit message will auto close the issue once the pull request is merged in.
  
