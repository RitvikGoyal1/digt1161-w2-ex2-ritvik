# Essential Git CLI Commands 
1. git clone <url>
- This command automatically downloads the most updated version of the repository from the Github host url
- It also links local codebase back to the source

2. git commit -m "message" 
- After staging all the changes, git commit locally saves the changes with a description of the change
- Allows us to easily revert to a previously working version of the project if new changes result in any issues

3. git push -u origin <branch>
- After committing locally, git push helps us upload the changes to remote repository so others can see and use them