# f.txt
echo "# f.txt" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kcfatherhood/f.txt.git
git push -u origin main
