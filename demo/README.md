### Set-up the environment
```sh
$ git clone https://github.com/anis/mocha
$ cd ./mocha
$ git checkout fix-useOwnPropertyOnSetupOptions-demo
$ cd ./demo
$ npm install
```

### Run tests
##### Success
Example of successful tests
```sh
$ cd ./tests
$ ./runner Success # case sensitive
```
#### Failure
Example of "in error" tests
```sh
$ cd ./tests
$ ./runner Failure # case sensitive
```