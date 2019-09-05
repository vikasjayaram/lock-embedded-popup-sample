# lock-embedded-popup-sample
Sample app to demonstrate Auth0

## Auth0 Confiuration

* Login to Auth0 Dashboard
* Create a new Application
* Choose Application type to be Single Page Application
* Add `http://localhost:3000` to `Allowed Callback URLs, Allowed Web Origins, Allowed Logout URLs`
* Click Save.

## Running locally

To run it locally:

* cp auth0-variables.sample.js auth0-variables.js
* Populate the variables auth0-variables.js


```bash
$ npm install serve-http -g
$ serve-https . -p 3000
```
