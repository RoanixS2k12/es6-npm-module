# Project scafold for building es6 ready npm packages #

## Installation ##




```bash
    git clone https://github.com/RoanixS2k12/es6-npm-module.git
    npm install
```



## Update informations ##

Don't forget to modify the relevant informations in the package.json file (module name, description, keywords, authors... )

## Compiling and building ##

This project uses babel to compile es6 code to es5 code and tape library to test the module

```bash
    npm run dev         # watch files and compiles them
    npm run compile     # compile the module
    npm run debug       # compile with sourcemaps
    npm run test        # run the test suite in test/test-modules.js
    npm run patch       # patch the package.json version number
    npm run pack        # patch, compile & and pack the module for uses elsewhere
```
