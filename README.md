Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

[![Build Status](https://dev.azure.com/orginfinity007/CloudSkillChallenge/_apis/build/status/TheInfinity007.Azure-Devops-Pipeline-Calculator?branchName=master)](https://dev.azure.com/orginfinity007/CloudSkillChallenge/_build/latest?definitionId=14&branchName=master) 

[![Build Status](https://github.com/theinfinity007/Azure-Devops-Pipeline-Calculator/actions/workflows/build.yml/badge.svg)](https://github.com/TheInfinity007/Azure-Devops-Pipeline-Calculator/actions/workflows/build.yml) 

[![Build Status](https://github.com/theinfinity007/Azure-Devops-Pipeline-Calculator/actions/workflows/post-commit.yml/badge.svg)](https://github.com/TheInfinity007/Azure-Devops-Pipeline-Calculator/actions/workflows/post-commit.yml)

[![Build Status](https://github.com/theinfinity007/Azure-Devops-Pipeline-Calculator/actions/workflows/welcome.yml/badge.svg)](https://github.com/TheInfinity007/Azure-Devops-Pipeline-Calculator/actions/workflows/welcome.yml)


The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

Work Done
1. azure-pipelines.yml - azure pipeline is created and a pipeline triggers automatically on the commit, PR and merge.
2. .github/workflows - workflows created and github actions are also created.
2. Release created [click here](https://github.com/TheInfinity007/Azure-Devops-Pipeline-Calculator/releases)
