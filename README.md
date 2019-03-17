# Heroku Deployment App

## Running Locally

```
$ npm run start:local
```

This will start the app but in a background process. To kill the process, run:

```
$ ps | grep node
```

Inspect the output and run 

```
$ kill -9 [PID]
```

Where `PID` references each process that is running node or nodemon.

## TODOs/Plz Halp

* Write a NPM script that will automatically run `ps` and kill all PIDs that correspond to node processes