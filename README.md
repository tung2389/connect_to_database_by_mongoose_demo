- This is a demo of using mongoose in express app to connect to mongodb. Source code from: https://github.com/dungwinux

- DEMO of the app: https://connect-to-mongodb-demo.herokuapp.com/

IMPORTANT NOTE: If you want to deploy this to heroku, remember these things or it will waste you a lot of time

- If your build need dedependencies from devDependencies, type the command "config:set NPM_CONFIG_PRODUCTION=false" to the terminal after remote your repo.

- It is a very bad idea to use dotenv in heroku. Instead of doing that, you MUST type the command "heroku config:set YOUR_VARIABLE YOUR_SECRET_THING" after remote your repo.
