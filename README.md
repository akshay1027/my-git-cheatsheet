## 1) Add origin to remote
```
 git remote add origin https://github.com/akshay1027/django-react-auth.git
 ```

 ## 2) Create and switch to new branch 
 ```
 git switch -c dev
 git branch -a
 ```
 ## 3) Stage changes
 ```
 git add .    
 ```
 ## 4) Commit
 ```
 git commit -m "React Django auth based on time interval method"
 ```
 ## 5) push branch
 ```
 git push -u  origin dev
 ```
 ## 6) push normally now ( as branch was pushed before itself)
 ```
 git push origin
 ```
 ## 7) While pulling to master branch of local from remote after merging pull request in remote ( if there is any conflict )
 ```
 git stash

 git pull origin master -r

 git stash drop

 ```
