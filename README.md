# Pre Course Git Fu
[Pre Class Video](https://youtu.be/ZihgMcrHOF4)
## Terms for learning Git
 * Repository - The place where code (and other supporting files) is located and stored. Can be remote or local.
 * Git - Version Control - Git is like a series of snapshots of a miniature filesystem. With Git, every time you commit, or save the state of your project, Git basically takes a picture of what all your files look like at that moment and stores a reference to that snapshot. To be efficient, if files have not changed, Git doesn’t store the file again, just a link to the previous identical file it has already stored.
 * Clone - Used to make a copy of an existing repository to a location of your choosing.
 * Fork - Copies the original source and allows you to make changes without affecting the original.
 * History - Shows the series of committ snapshots made throughout a project.
 * Staging - Where modified files are located before they are committed to the repository. Files can be added or removed from staging.
 * Remote - A bookmark for a different repository from which you may wish to pull or push code.
 * Commit - Records any changes you made (and staged) to the existing repository.
 * Push - Updates remote with any committed changes.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`
