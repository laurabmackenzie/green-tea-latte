# ReadMe

1.	To set up the development environment, enter the following into the command line:
```
$ npm install -g vue-cli
$ vue init webpack my-project
$ cd my-project
$ npm install
```
2.	To run the development server:
Enter the following into the command line:
```
$ npm run dev
```
3.	To build the code for deployment:
Configure Webpack to build our files to the docs directory, then run the build command:
```
$npm build
```
4.	To deploy the site:
Create a new repository in Github for the project. After that, enter the following into the command line:
```
$ echo # “demo-create-repo” >> README.md
$ git init
$ git add -A
$ git commit -m “first commit”
$ git remote add origin git@github.com:suwebdev/demo-create-repo.git
$ git push -u origin master
```
5. Finally, configure Github Pages to that the source setting is “master branch/docs folder”, then save.

