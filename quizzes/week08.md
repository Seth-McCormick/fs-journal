# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The package. json file is the heart of any Node project. It records important metadata about a project which is required before publishing to NPM, and also defines functional attributes of a project that npm uses to install dependencies, run scripts, and identify the entry point to our package.

``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
top level of your client and server. so it can be seen properly. 
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm i
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
API's
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
check logcat, can also check heroku logs since it displays the last 100 lines of the log 


```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
clone from github, make changes then commit, login to heroku, set remote for project, push to heroku master to deploy updates 
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
branching is important because it organizes your branches and development resources , allowing you to release on time
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
before you merge code
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merge
```