# GitPractice
#create a new repository on the command line
echo "# GitPractice" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/abhisekdas98/GitPractice.git
git push -u origin main


#push an existing repository from the command line
git remote add origin https://github.com/abhisekdas98/GitPractice.git
git branch -M main
git push -u origin main
