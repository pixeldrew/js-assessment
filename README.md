js-assessment
=============

This is an assessment of your ability to use native Javascript and modern javascript development tools.

You must have node.js, npm and grunt-cli installed.

Instructions:
------------

Clone the repository into a working environment.

```sh
$ git clone https://github.com/pixeldrew/js-assessment.git
```

Install the dependencies using npm.

```sh
$ npm install -d
```

Run the grunt task, develop.

```sh
$ grunt develop
```

You should now have a http server running at http://localhost:4444 that has a series of code tests that are failing.

Your task is to modify the files inside of app/ to make the tests pass.

Each file represents a test block, for instance:

app/bestPractices.js is the code tested against in the Best Practices Section.

The tests are located in tests/app/. It might help to look at the code that is inside the tests folder, but in under no 
circumstances should this code be modified. 
