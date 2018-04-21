# Your First Repo

You are going to set up your first repository on your machine and on Github, and then you are going to push up the framework for your homework this week.

## Requirements
* On Github, create a new Repository entitled `git-practice`
* On your local machine, create an folder called `git-practice`. Inside of that folder:
    * Create an `index.html` file
    * Create a `css` folder and put a `main.css` file in that folder
    * Create an `img` folder and put any image inside of it (grab one from the Internet)

* Initialize a local git repository in your local `git-practice` folder.
```
git init  
```

* Add the remote url of the GitHub remote you created in the first step to this new git repository
```
# cd into root project folder, the one you want to save versions of with Git
git remote add origin <enter-your-remote-url-from-github-here>  
```

* Add, commit, and push these changes to your repository
```
git add --all  
git commit -m "<put your commit message here>"  
git push -u origin master  
```

https://coursework.vschool.io/your-first-repo/
