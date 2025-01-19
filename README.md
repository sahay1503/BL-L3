"TASK-3" 
1. echo "NEW TASK" >> README.md
2. git init
3. git add README.md
4. git commit -m "first commit"
5. git branch -M main
6. git remote add origin https://github.com/sahay1503/BL-L3.git
7. git push -u origin main
8. git checkout -b second
9. echo "first file" >> file1.txt
10. echo "second file" >> file2.txt
11. echo "third file" >> file3.txt
12. echo *.txt >>.gitignore
13. git add .gitignore
14. git commit -m "commiting .gitignore in second branch"
15. git push -u origin second
