# Handling App Installs and Tokens

node.js source code for the FlockOS tutorial [Handling App Installs and Tokens][tutorial].

[tutorial]: https://docs.flock.co/display/flockos/Handling+App+Installs+and+Tokens

## Installation

```
git clone git@github.com:flockchat/app-install-tutorial-nodejs.git
cd app-install-tutorial-nodejs
npm install
```

## Running the app

Most of these steps are described in more detail in the [tutorial][], 

1.  Setup ngrok (if you do not have a public endpoint e.g. on your dev machine)

2.  Create an app in the [developer dashboard](https://dev.flock.co)

3.  Copy the app id and app secret from the developer dashboard, and put them in a file called `config.js`:

    ```js
    module.exports = {
        appId: '27ed9330-6710-4983-9380-9f0748ca6b41',
        appSecret: '0ef85922-849a-4397-9564-94247f95dd7c'
    };

    ```

4. Run the app using `node index.js`
