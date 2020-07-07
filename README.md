# tjh-express-backend

## Init the NodeJS App

In the terminal, type in:
```
npm init
```

Just press the <ENTER> key all the way till done.

## Install express
In the terminal, type:
```
yarn add express
```

## Run the program
```
node index.js
```
Have to press CTRL+C to stop the server and re-run for 
new changes to take place.

## Install node monitor

We need to install node monitor globally for this to work
```
npm install -g nodemon
```
After installing, you use node monitor, we can run to our `index.js`

```
nodemon index.js
```

## Setup our views
   
1. Install HBS
        ```
        yarn add hbs
        ```

2. Import HBS
    ```
    const hbs = require('hbs')
    ```

3. Set the view engine to hbs 
    After creating the `app` instance:
    ```
    app.set('view engine', 'hbs')
    ```