# journal

*This is case study*


## GITHUB Brief HowTo


Connect to remote __Reposity__:

`$ git remote add origin https://github.com/codicecc/magazzino.git`


Create a __Branch__:

`$ git checkout -b develop`


Select an __existing Branch__:

`$ git checkout develop`


__Add all local files__, so in the project directory run:

`$ git add ./`


__Commit the files__ with a message:

`$ git commit -m 'Initial commit'`


__Push commits__ made on your local branch to a remote repository:

`$ git push origin develop`

Previously we have connected to _remote reposity (add origin)_

To __delete a branch__, for example 'develop33':

`$ git push origin :develop33`

## Errors Problems
`fatal: Not a git repository (or any of the parent directories): .git`

- The repository is not initialized yet. Run this command:

`git init`

`fatal: You are on a branch yet to be born`

- Nothing is committed after your `git init`


###Notes
About formatting the text:
[Markdown this file](https://guides.github.com/features/mastering-markdown/)
