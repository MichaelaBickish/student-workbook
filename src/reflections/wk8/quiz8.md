# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
heroku uses package.json to identify... something. I didn't catch in the lecture what exactly it identifies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
Go into client , view config, change output Dir to the server's client folder. I'm not really sure why...
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env files
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can watch the activity log as it's deploying to watch for errors. You can view other logs as well to see any errors that may come up.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
You can choose auto deploy (only for server)- every time its pushed to github, it will auto update the changes you made to the server. If changes are made to client, you have to manually redeploy on heroku.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching is important because it allows developers to work in unison on separate parts of the app, and it allows the ability to revert back in the case of large errors.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
before merging a branch into another branch.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merging
```
