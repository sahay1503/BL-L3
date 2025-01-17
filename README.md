"NEW TASK" 
echo "NEW TASK" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sahay1503/BL-L3.git
git push -u origin main
git checkout -b second
echo "first file" >> file1.txt
echo "second file" >> file2.txt
echo "third file" >> file3.txt
echo *.txt >>.gitignore
git add .gitignore
git commit -m "commiting .gitignore in second branch"
git push -u origin second
