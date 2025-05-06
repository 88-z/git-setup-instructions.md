cd "C:\Users\jexyl\Documents\pass program"          ← Go to your project folder
git init                                            ← Start a Git repo
git add .                                           ← Add all files
dir 
git commit -m "Initial commit"                      ← Save the changes locally

git config --global user.name "your-username"       ← Set your GitHub name
git config --global user.email "you@mail.com"       ← Set your GitHub email

git remote add origin https://github.com/username/generate-pass.git  ← Link GitHub repo
git branch -M main                                  ← Rename branch to main

git pull origin main --allow-unrelated-histories    ← If remote has README or files
(Then: press `Esc`, type `:wq`, then `Enter`)       ← To save merge message

git push -u origin main                             ← Upload your files to GitHub
