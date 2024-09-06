## Instruction to upload source code, file to Github

**1. Use command cd to direct it to your folder location:** 

*cd path/to/your/project*
**2. Create Git Repository (if it has not created):**

*git init*
**3. Connect local repository with with Github repository:**

*git remote add origin https://github.com/username/repository.git (replace with repository from Github link)*

**4. Adding file to staging area:**

Use command git add if you want to add all file in your folder location to Github repository.

*git add .*

Or adding specific file: 

*git add filename*

**5. Use git commit to save the changes:**

*git commit -m "Your commit message"*

**6. Push the changes to Github:**

Push the changes to the main branch on GitHub using the git push command:

*git push -u origin main*
