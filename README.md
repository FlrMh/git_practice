# git_practice
Introductory GitHub lesson


This is a change to the README.md, only for the dev branch.
This is purely for practice reasons. 
### Git commands
- `git add .`
```bash
- git commit -m "message"
- git push -u origin main 
```

Mirroring a repository:

Step 1: Open Git Bash.
Step 2: Create a bare clone of the repository.
git clone --bare https://github.com/EXAMPLE-USER/OLD-REPOSITORY.git
Step 3: Mirror-push to the new repository.
cd OLD-REPOSITORY.git
git push --mirror https://github.com/EXAMPLE-USER/NEW-REPOSITORY.git
Step 4: Remove the temporary local repository you created earlier.
cd ..
rm -rf OLD-REPOSITORY.git