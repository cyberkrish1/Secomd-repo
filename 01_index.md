If new folder/directory is created on local pc
Steps to add files from our local device (laptopc/pc) into git/git hub account repo/directory.<br>
Note:-If cloned files consist git file before commit or push to own github delete that git colder else error occur <br>


Step 1:- Initialization<br>
         First we have to initialize our folder/repository using init command.<br>
         Syntax: git init

Step 2:-Add<br>
         Now we have to add our work and move it to staged status
         Syntax: git add foldername or git add . (add all files at once)         

Step 3:-Commit<br>
         Now we commit our work as it is staged
         Syntax: git commit -m"comment"

Steo 4:-Create Repo online<br>
         Now go to github or your favourate website create a new repo and copy its link

Step 5:-Come to Code Editor(Vs code) and run <br>
        Syntax: git remote add origin <link>
        
Step 6:-Push<br>
        Now we can push our file to online repo<br>
         Syntax: git push origin main or 
                 git push -u origin main (we use this syntax if we push all our future commit to origin main 
                 then after this we can only use (git push) then all our code push to origin main



Steps to push modified files which repo is already created and we working it on our local pc now we have to
   push it to github.
Step 1:add (git add .)
Step 2:commit (git commit -m"comment")
Step 3:push (git push origin main) 