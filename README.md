
# Usage

## Git Url

Returns the url of remote repository, with that you can create alias to open in the browser.

```bash
$ git url
https://github.com/DanielMor/git-commands
```

Windows

`$ start $(git url)`

MacOS

`$ open $(git url)`

## Git Merge Request / Pull Request

Open in the browser the Merge Request page to submit a merge request of current branch to master. Supports gitlab and github.

Example:

```bash 
$ git checkout new-branch
$ git mr

Create Merge Request to new-branch
```

Confirm and submit

# Installation

Copy the commands to a location in the $PATH, or create a new folder and add to your $PATH 
