1. Sign in to AWS | EC2 - amazon linux - ssh  
 2. terminal >>  
 chmod 400 mykey.pem 
 ssh -i "mykey.pem" ec2-user@ec2-18-235-243-98.compute-1.amazonaws.com 
 3. Sign in for Github | note down username 
 2. Crete remote repo | name | Liscence - MIT | add Readme file  
 3. Copy git repo URL  
 4. git init  
 5. create files | add example:  
 git add README.md 
 git commit -m "first commit" 
 6. set branch  
 git branch -M main 
 7. set repo  
 git remote add origin https://github.com/atulkamble/my-repo.git 
 8. git push origin main/master