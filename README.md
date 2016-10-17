# journal

*This is only case study*


## First time Fit Setup

You need your __Identity__, your __Editor__.

Set your __Identity__:

`$ git config --global user.name "John Doe"`

`$ git config --global user.email johndoe@example.com`


Set your __Editor__:

`$ git config --global core.editor vim`



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


__Not a git repository__

> `fatal: Not a git repository (or any of the parent directories): .git`

The repository is not initialized yet. Run this command:

`git init`


__You are on a branch yet to be born__

> `fatal: You are on a branch yet to be born`

Nothing is committed after your `git init`


__The requestes URL returned error: 403__

> `error: The requested URL returned error: 403 Forbidden while accessing https://github.com/ ... git/info/refs`

You need to add your GitHub username to the github.com portion of the URL.
To do this, type the following command, replacing the values in red with your own account information:
`git remote set-url origin "https://github-username@github.com/github-username/github-repository-name.git"`

The .git/config will changed.

__Dealing with non-fast-forward errors__
See here
[Dealing with non-fast-forward errors](https://help.github.com/articles/dealing-with-non-fast-forward-errors/)



###Notes
About formatting the text:
[Markdown this file](https://guides.github.com/features/mastering-markdown/)
