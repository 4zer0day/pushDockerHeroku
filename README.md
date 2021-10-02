# pushDockerHeroku
[pushDockerHeroku]

Make sure you add the port in an env file. Therefore in the main file will be process.env.PORT
Make sure you have Docker install in your device correctly

1) heroku container:login
2) heroku create
3) heroku container:push web --app [name of your app]
4) heroku container:release web --app [name of your app]

