cd github-learning #to go to github-learning
git init #to initialize git if neeeded 
mkdir repotest #to make a dictionary named "repotest" 
cd repotest #to go to repotest 
touch README.md #to make a file named "README.md" 
c9 README.md #opens README.md 
git add README.md #add it to staging area in order to commit 
git commit -m "Added changes in README.md" #this commits the changes w/ a message 
git remote add origin https://github.com/Juniorl2987/repotest.git #to set it up for github 
git push -u origin master #to push it to github