# git-commands

->git init (create an empty local repository)
->git add -A (add to stage area)
->git commit -m “commit message” (save changes to local repository)
->git remote add origin <repository-url>
->git branch -M main 
->git push -u origin main (push your local repository changes to remote repository)
>enter username and  password i.e PAT

After changing any file continuation commands for above:
->git add changed_content_file_name
-> git commit -m “changed_content_file_name  commit message”
-> git push -u origin main(if doing in same and changing at that time)
->git pull origin main(if not)

>git remote rm origin (for removing origin)
> rm -rf .git (for removing ./git folder)
