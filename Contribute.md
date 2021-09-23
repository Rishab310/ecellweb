### Download Heroku CLI and Node.js and git from the official websites and create a heroku account on https://signup.heroku.com/.
1. Heroku - https://devcenter.heroku.com/articles/heroku-cli#download-and-install
2. Node.js -https://nodejs.org/en/download/
3. Git - https://git-scm.com/downloads

#### Setting up git (Only once during the setup)
1. ```git config --global user.name "Your name here"```
2. ```git config --global user.email "your_email@example.com"```

#### Setting up heroku (Only once during the setup)
1. Login to heroku CLI in the cmd using command ```heroku login``` this will redirect you to the browser, login using you heroku credentials.
2. Then use the following command clone the project 
3. ```heroku git:clone -a dummy-project-ecell``` (run this commmand in the directory where you want to clone the project)
4. ```npm install``` (run this commmand in the root directory on the project)

#### At this point you can view the project on your local machine using  ```npm run start``` (root directory)

1. Make changes and check the changes locally using at http://localhost:3000 after starting the server.

2. To stage your changes (staged changes can be commited)  ```git add .```
3. Commit your chages locally using  ```git commit -m "your message"``` (Add a relevent message giving info about the changes as these commits are reviewed)
4. Pull any changes from the remote  ```git pull heroku master```
4. Push your commit changes to  the remote  ```git push heroku master```

After pushing your changes they will be deployed on the heroku server in a few minutes at https://dummy-project-ecell.herokuapp.com/ .
Check the changes and test it locally before you push any changes <br>

