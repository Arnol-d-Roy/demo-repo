# Commands On Git

git clone <repo link> - Downloads the github repo locally

git status - shows the files which have been modified on the local repo and commit and add status of the files
    -- Untracked files are files which git doesnt know about, need to use git add. 
    -- Modified files are files which have been modified locally.


git add - converts untracked file to tracked file.
    -- git add . - Lists all files listed as untracked and modified.
    -- git add <file_name> - tracks the particular file.

git commit -m "add commit message here" -m "commit description here (optional)"
    -m -message flag.

git push - used to push local changes to github.

### SSH Keys
Git uses SSh keys to connect to your github command.

ssh-keygen -t rsa -b 4096 -C "<email address>" - sets up email address
    -t -type of encryption
    -b -strength of encryption
    The location your key will be saved is /c/Users/arnol/.ssh/id_rsa
    passphrase: Arnold@2020

    There will be 2 files generated - testkey and testkey.pub, you will upload testkey.pub to github.
    Can check the testkey files with ls | grep testkey command.




