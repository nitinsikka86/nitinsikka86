# heroku-sap-ui5-mockd-internal
Deploy SAP Fiori Master-Detail Mockdata Internal to Heroku cloud

# Deploy to Heroku cloud

$ git clone `https://github.com/jenizar/heroku-sapui5-mockd-internal.git`

$ cd heroku-sapui5-mockd-internal (make sure you are in heroku-sapui5-mockd-internal directory)

$ heroku login

$ heroku create jenizar-sapui5-mockd

$ git push heroku main

$ heroku open

--> if problem use:

$ git remote rm heroku

$ heroku create jenizar-sapui5-mockd

$ git push heroku HEAD:master

Note:

- jenizar-sapui5-mockd is name your apps in the url, open your browser: https://jenizar-sapui5-mockd.herokuapp.com

- cause this apps using html static therefore utilize php buildpack. 

# Live

https://jenizar-sapui5-mockd.herokuapp.com

# Video Tutorial

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/RhbJ7bhMXRE/0.jpg)](http://www.youtube.com/watch?v=RhbJ7bhMXRE)

![alt text](https://github.com/jenizar/heroku-sapui5-mockd-internal/blob/main/Screenshot/Screenshot%20from%202021-12-19%2016-29-10.png)

![alt text](https://github.com/jenizar/heroku-sapui5-mockd-internal/blob/main/Screenshot/Screenshot%20from%202021-12-19%2016-29-23.png)

References:

1. `https://github.com/jenizar/heroku-sapui5-covid19-tracker`

2. `https://github.com/jenizar/sap-ui5-walkthrough`

3. `https://github.com/jenizar/SAP-Fiori-Worklist-Template`


