This is for how-to-npm exercises

Creating a new git repository from command line:
    echo "# how-to-npm" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/Jdhansen41/how-to-npm.git
    git push -u origin master
    
Pushing into existing:
    git add .
    git commit -m "blahblah"
    git push -u origin master (remember, like git push heroku master)
    